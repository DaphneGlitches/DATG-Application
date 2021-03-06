# DATG Band App Beta

This is the first version of the web application for the blues/psych/rock band **Daphne + The Glitches'**.

## Navbar

Each page will include a navbar header that will offer different options, depending if the user is logged in or not.
Base options are:

- Home
- Music
- Tour
- Contact
- Login
- Register

When a user is logged in the Login and Register options will be replaced with a welcome message to indicate the user is
logged in, as well as a Logout button, and access to the Profile page will also be available.

## Home (index)

This is the landing page for the application. It contains a carousel of recent photos and some basic info about the
band.

## Music

This page contains an iFrame for YouTube video of DATG single 'Outgoing Male'.

## Tour

This page will display a table including upcoming shows for the band with links to purchase tickets. The table will
include:

- City
- Venue
- Date
- Ticket prices for pre-sale and day of show (DOS)

When logged in, a user would be able to create new tour dates via the 'Create Date' button on the bottom of the page.
These tour dates will be stored on a database table, and are editable and deletable via the Edit/Delete buttons that are
also only viewable to logged in users.

## Tour_Date

This is the page used to add new shows to the tour_date table, as well as edit any date that is already present when
the 'Edit' button is clicked.

## Contact

Form in order to contact the band, asking for a name, email, and message to be input.

## Profile

Page that logged in users will see that can be used to update the description attached to their profile, as well as
update their password.

## Login

This page will be used to login to a user account once one has already been created using the Registration page. The
required fields to login are Username and Password.

## Registration

This page will be used to register new users to the site. Users will be prompted to fill in their E-Mail, Username and
Password in order to register as an official user of the site. On a successful Registration the user will be redirected
to the Login page.
