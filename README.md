# User Centric Frontend Development Milestone Project

[Link to website](https://andreasdk.github.io/ariana/)

For this project, I made a static frontend website for the singer Ariana Grande that includes a news section, a music section, a video section, a tour section, and a newsletter section. I also included social media links.

---

## UX

The purpose of the website is to be able to get news, listen to music, watch music videos, get tour information, signup for a newsletter, and get social media links.
Here is a link to the [mockup.](https://app.moqups.com/K3PEm0KV9a/view?fit_width=1)

#### User Stories
* As a user, I want to have news so I can see any new updates
* As a user, I want to be able to listen to music, and see artwork
* As a user, I want to have streaming links to music so I can listen online
* As a user, I want to have links to buy the music so I can listen offline
* As a user, I want to be able to watch new music videos
* As a user, I want to see information about any upcoming tours
* As a user, I want to have links to buy tickets to attend a tour
* As a user, I want to be able to subscribe to a newsletter to receive new updates from the singer
* As a user, I want social media links so I can follow the singer online

---

## Features

#### Existing Features
* The first feature is a navbar, with links to each section of the page
* Underneath the navbar, I included a hero image of Ariana Grande with no text to give a visual impact
* The news section is made up of image cards with a short text overlay. Each card is clickable and brings the user to a relevant part of the page. When the user hovers over the card, the text fades and a relevant icon appears over the image.
* The music section allows users to see information about current and past albums. On desktop view, the content in each row alternates position, while it stacks in mobile view. There is a link to Spotify for each album, and a dropdown button with links to music stores. The dropdown button is pushed slightly up on hover.
* The video section includes a music video that scales responsively.
* The tour section is made up of a table with dates, venue and city, and a link to buy tickets. The buy ticket link inverts color on hover.
* There is a newsletter signup which prompts the user to enter their email and click on a submit button.
* At the bottom of the page is a footer with social media links which users can click on and be directed to the respective page.

#### Features Left To Implement
* I considered adding more text to the news section cards to make it really obvious what the cards were for, but ultimately scrapped it.

#### Features Changed From Mockup
* I has designed the hero image to be right aligned in desktop taking up half the screen, with a left-align about section taking up the other half. When I looked at the official Ariana Grande website, I noticed there is not much text, it's very image heavy. I decided that a user visiting her website would be aware of who she was and didn't go ahead with the about section, and changed the hero image to be take up the full height and width on all devices.

---

## Technologies Used

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) is the markup language I used to create the website content.
I tried to use semantic HTML where possible.
* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) was used to style the content of the page. I used CSS to set colors, underline effects, headings, text, hover effects, and to make content responsive.
* I used [Bootstrap 4](https://getbootstrap.com/) for responsive grid layout, alignment, column sizing, navigation and utilities.
* I used [jQuery](https://developer.mozilla.org/en-US/docs/Glossary/jQuery) to give the transparent navbar a background color on scroll.

---

## Testing
* I validated my HTML code with [WC3 HTML Validator](https://validator.w3.org) and got 'Document checking completed. No errors or warnings to show.'.
* I validated my CSS code with [WC3 CSS Validator](https://jigsaw.w3.org/css-validator/) and got 'Congratulations! No Error Found.'.

* I used Chrome development tools to test how my website looked on mobile and desktop. I also used c9 as a sort of sandbox for ideas I had, to see how they would look on the site.

<dl>
  <dt>News links</dt>
  * News cards should show a relevant icon on hover, and direct user to relevant section on click. &#10004;
 </dl>