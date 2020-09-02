# Frontend Mentor - Ping coming soon page

![Design preview for the Ping coming soon page coding challenge](./design/desktop-preview.jpg)

## What is this?
This is my response to a front-end coding challenge from [Frontend Mentor](https://www.frontendmentor.io). Frontend Mentor provides great development challenges alongside beautiful designs, enabling you to build your skills using realistic projects.

I plan to take on most, if not all, of the free challenges in order from easiest (_'Newbie'_) to hardest (_'Advanced'_).

## The challenge
__Challenge #8__<br>
__Difficulty: Newbie__

This challenge was to build out a Coming Soon page and get it looking as close to the design as possible.

Users should be able to:
- View the optimal layout for the component depending on their device's screen size
- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Submit their email address using an `input` field
- Receive an error message when the `form` is submitted if:
	- The `input` field is empty. The message for this error should say *"Whoops! It looks like you forgot to add your email"*
	- The email address is not formatted correctly (i.e. a correct email address should have this structure: `name@host.tld`). The message for this error should say *"Please provide a valid email address"*

## My approach
I started by building out the basic __HTML__ page structure, making sure the page layout made sense at a fundamental level, particularly for screenreader users.

From there I took a mobile-first approach, completing styling and layout for a 375px viewport width before building out media queries to cater to larger widths.

I used __Sass__ to easily implement elements from the `style-guide.md` provided.

For input validation, I used [__jQuery Validation__](https://jqueryvalidation.org/) with custom message and highlight rules for the error states.

The end product is hosted on Vercel - https://ping-single-column-coming-soon-page-flax.vercel.app/

Cheers! 🍻
