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

## Technologies Used

- HTML5
- CSS3
- [Bootstrap v.4.4](https://getbootstrap.com/docs/4.4/getting-started/download/) - Bootstrap allowed me to add some JavaScript
functionality to the website, such as the Navbar Toggler, the Carousel, and the Modal.

## Testing

### Contact Form

   1. Submitting empty form displays, *Please fill in this field* for *Your Name*.
   1. Submitting form with *Your Name* filled displays, *Please fill in this field* for *Your Email*.
   1. Submitting *Your Email* without an *@* symbol displays *Please include an '@' in the email address. '#' is missing an '@'*.
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

    1. *Your Email* will submit despite not having a proper address format. An error only displays when an '@' symbol is abscent.
    for example, 'a@a' will submit.


### Login

   1. Clicking on Login will successfully bring up the _LOGIN_ modal on every page.
   1. Clicking Login with empty inputs will display an error message.
   1. Clicking Login with only the email filled will display an error message.
   1. Submitting _Your Email_ without an @ symbol will display an error message.
   1. Clicking Login with only the password filled will display an error message.
   1. Clicking Login with both filled but a password shorter than 8 characters will display an error message.
   1. Form will submit when email is entered with a password with 8 or more characters.
   1. Clicking on the register hyperlink will successfully close the Login modal and bring up the register Modal.

1. Bugs:
   1. When the Modal appears in a browser window, the modal has a padding-right: 17px; When this happens the background image on
      index.html will stretch.
   1. When a user is registering and enters their repeat password, the form will submit even when both passwords do not match. Some JavaScript
      may fix this.

## Deployment

## Credits

### Content

The quote on the homepage beneath 'Where we meet' that was attributed to C.S. Lewis, "That part of Rostrevor which overlooks Carlingford Lough
is my idea of Narnia." was copied from [Visit Mourne Mountains](https://www.visitmournemountains.co.uk/ChroniclesofNarnia)

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
