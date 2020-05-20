# Mourne Book Club

The [Mourne Book Club](https://paulloy.github.io/Mourne-Book-Club/) has been rapidly attracting new members, and this project
aims to accommodate that growth through being a hub where members can keep up to date with important club information, such
as: what books are being read, who is reading them, and when will the meetings take place.
For potential members, this project serves as an easy way for them to learn about what the club is and how they can join.
The Mourne Book Club aims to become the central node in a network of book clubs in the Newry and Mourne district.

## UX

This website is designed for users within Newry and Mourne who are interested in joining a local book club.

- User1:
  - user experience (UX)

[Project Wireframe](MourneBookClubWireframe.pdf)

## Features

### Bootstrap Carousel

The user is first greeted with a carousel that features all the books that will be covered at their respective meetings.
For members, this is the most important information. For new users, this is an advertisement of the electic range of books
covered by the club. There is a book for everyone.

### Bootstrap Modal

A login modal appears whenever _Login_ is selected in the navbar. This allows current members to sign in. If the user is
not already a member, then they can register.

### Contact Form

The contact form allows users to contact the club with any further questions they have that are not already covered on 
the FAQ page.

### Members page

This allows a user to view the current club members, their names, the books they are reading, and s small gallery
with photos from the club.

### FAQ page

The frequently asked questions page allows a new user to search for questions the club is frequently asked. This allows
the user to have their common questions quickly addressed without having to wait for a response after submitting a 
message on the contact form.

### Contact page

This page allows a user to calculate how far they are from the club on google maps. The address, and contact details are 
available for users who would like to ring the club or email it.
The contact form allows a user to directly message the club with a query. Any new frequently asked questions will be 
added to the FAQ page.

## Technologies Used

- HTML5
- CSS3
- [Bootstrap v.4.4](https://getbootstrap.com/docs/4.4/getting-started/download/) - Bootstrap allowed me to add some JavaScript
functionality to the website, such as the Navbar Toggler, the Carousel, and the Modal.

## Testing

### Contact Form

1. Submitting Form

   1. Submitting empty form displays, *Please fill in this field* for *Your Name*.
   1. Submitting form with *Your Name* filled displays, *Please fill in this field* for *Your Email*.
   1. Submitting *Your Email* without an *@* symbol displays *Please include an '@' in the email address. 'a' is missing an '@'*.
   1. Submitting *Your Email* with "a@" will display *Please enter a part following '@'. 'a@' is incomplete.*
   1. Submitting *Your Email* with an *@* symbol displays, *Please fill in this field* for *Your Message*.
   1. Submitting the form with *Your Name*, *Your Email*, and *Your Message* filled will successfully submit the form.
   1. Submitting the form with *Your Phone Number (Optional)* and/or *Join Our Mailing List (Optional)* filled alongside the
   required information will successfully submit the form.

1. Responsive design

    1. When the screen width is greater than 767px, the contact form will remain in a row with two columns. The left column
    featuring the *Your Name*, *Your Email*, *Your Phone Number (Optional)*, *Join Our Mailing List (Optional)*, and
    their respective labels and checkbox. The right column featuring *Your Message*, its label, and a *Send Message* button.
    1. At 767px, the two columns collapse into a single column. The right column drops below the left.
    1. At 576px, the font size of the labels reduce in size.
    1. The Contact form remains responsive for all screen widths.
    1. The inputs remain responsive by maintaining an 80% width of their containers at all times.

1. Bugs 

    1. At this stage of the project, the form submits data to [Code Institute Form Dump]("https://formdump.codeinstitute.net")
   to confirm that the form will successfully submit data. They may become fully functional at a later stage in development.
    1. *Your Email* will submit despite not having a proper address format. An error only displays when an '@' symbol is abscent.
    For example, 'a@a' will submit.


### Login

1. Click Login

    1. Sign in Modal appears on page.
    1. Logging in with an empty form displays *Please fill in this field* for *Your Email*.
    1. logging in *Your Email* without an *@* symbol displays *Please include an '@' in the email address. 'a' is missing an '@'*.
    1. Logging in *Your Email* with "a@" will display *Please enter a part following '@'. 'a@' is incomplete.*
    1. Logging in *Your Email* with "a@a" will display *Please fill in this field* for *Your Password*.
    1. Logging in *Your Password* with less than eight characters will display *Please lengthen this text to 8 characters
    or more (you are currently using using 1 character).*
    1. Logging in with a password of 8 characters or more will successfully submit.

1. Clicking; Not a member? Register

    1. Sign Up Modal appears on page. 
    1. Registering in with an empty form displays *Please fill in this field* for *Your Email*.
    1. Registering *Your Email* without an *@* symbol displays *Please include an '@' in the email address. 'a' is missing an '@'*.
    1. Registering *Your Email* with "a@" will display *Please enter a part following '@'. 'a@' is incomplete.*
    1. Registering *Your Email* with "a@a" will display *Please fill in this field* for *Your Password*.
    1. Registering *Your Password* with less than eight characters will display *Please lengthen this text to 8 characters
    or more (you are currently using using 1 character).*
    1. Registering with a password of 8 characters or more will display *Please fill in this field* for *Repeat Password*.
    1. Registering *Repeat Password* with less than eight characters will display *Please lengthen this text to 8 characters
    or more (you are currently using using 1 character).*
    1. Registering with a password of 8 characters or more will successfully submit.

1. Bugs:
   1. At this stage of the project, the Login and Register forms submit data to [Code Institute Form Dump]("https://formdump.codeinstitute.net")
   to confirm that the forms successfully submit data. They may become fully functional at a later stage in development.
   1. When the Modal appears in a browser window, the modal has a padding-right: 17px. When this happens the background image on
      index.html will stretch to fill this extra 17px, then will return to its normal size when the modal is closed.
   1. When a user is registering and enters their repeat password, the form will submit even when both passwords do not match. Some JavaScript
      may fix this.

1. Responsive design
    1. At widths greater than 575px, the Login/Register modals will remain the same width.
    1. At widths less than 576px, the Login/Register modals will stretch to fill the entire screen width.

### Carousel

1. Carousel functionality
    1. When the right carousel slider icon is clicked, the current slide will slide left, and a new slide will enter from 
    the right.
    1. When the left carousel slider icon is clicked, the current slide will slide right, and a new slide will enter from 
    the left.
    1. By default, when the pointer is not hovering above a carousel slide, the carousel slides will slide left and 
    a new slide will enter from the right.
    1. Each slide has a Learn More button which will successfully take the user to the respective GoodReads page of each book.

1. Responsive design
    1. At widths less than 992px, the carousel height will decrease, the sizes of all its contents will decrease. The image widths, 
    button size, and font size.
    1. At 576px, the image, and Learn More button, will drop below the content that was to its right. The carousel height will increase
    and the content will all reduce in size. Carousel sliders will decrease in size.
    1. At 450px, the translucent container will increase in size so that the carousel sliders appear above it.


## Deployment

This project was deployed with GitHub pages. It can be run locally using GitPod.

## Credits

### Content

The quote on the homepage beneath 'Where we meet' that was attributed to C.S. Lewis, "That part of Rostrevor which overlooks Carlingford Lough
is my idea of Narnia." was copied from [Visit Mourne Mountains](https://www.visitmournemountains.co.uk/ChroniclesofNarnia)

Google maps was copied from [Google Maps]("https://www.google.com/maps/place/Rostrevor,+Newry/@54.1068079,-6.2039405,14z/data=!3m1!4b1!4m5!3m4!1s0x4860d709523d0af3:0x40a379b46bb71a68!8m2!3d54.10073!4d-6.2003999").

### Media

All Media photos were sourced using [Google Images](https://www.google.co.uk/imghp?hl=en&tab=wi&ogbl),
except for the images in _Book cover image address_ which were sourced from [GoodReads](https://www.goodreads.com/), and
the Mourne Book Club logo which I created using the MeathFLF font by [Casady & Greene](https://www.fontspace.com/casady-and-greene)
on the [GNU Image Manipulation Program](https://www.gimp.org/).

- [Mourne Book Club Logo](img/mournelogo2f312c.png)
- [MeathFLF](https://www.fontspace.com/meathflf-font-f1247)
- [Book cover image address](img/book-covers/bookcoveraddress.txt)

- [Carousel background image address](img/carousel-slides/Image-Address.txt)
- [Gallery image address](img/gallery/gallery-images.txt)
- [Members image address](img/members-images/MembersImageAddress.txt)
- [About section image address](img/About-section-image-addresses.txt)

### Acknowledgements

- I received inspiration for this project from conversations with my friends Tomás M, Kamil M, Eoin M, and Conor S.
