# User Centric Frontend Development Milestone Project

[Link to website](https://andreasdk.github.io/ariana/)

For this project, I made a static frontend website for Ariana Grande that includes a news section, a music section, a video section, a tour section, and a newsletter section. I also included social media links.

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
* I had designed the hero image to be right aligned in desktop taking up half the screen, with a left-align about section taking up the other half. When I looked at the official Ariana Grande website, I noticed there is not much text, it's very image heavy. I decided that a user visiting her website would be aware of who she was and didn't go ahead with the about section, and changed the hero image to be take up the full height and width on all devices.

---

## Technologies Used

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) is the markup language I used to create the website content.
I tried to use semantic HTML where possible.
* [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) was used to style the content of the page. I used CSS to set colors, underline effects, headings, text, hover effects, positioning with flexbox, and to make content responsive.
* I used [Bootstrap 4](https://getbootstrap.com/) for responsive grid layout, alignment, column sizing, navigation and utilities.
* I used [Google Fonts](https://fonts.google.com/) for the font families
* I used [jQuery](https://developer.mozilla.org/en-US/docs/Glossary/jQuery) to give the transparent navbar a background color on scroll.

---

## Testing
* I validated my HTML code with [WC3 HTML Validator](https://validator.w3.org) and got 'Document checking completed. No errors or warnings to show.'.
* I validated my CSS code with [WC3 CSS Validator](https://jigsaw.w3.org/css-validator/) and got 'Congratulations! No Error Found.'.

* I used Chrome development tools to test how my website looked on mobile and desktop. I also used c9 as a sort of sandbox for ideas I had, to see how they would look on the site.

#### Changes Made From Testing
* I changed the navbar to fixed-top following recommendations from CI Students in Slack
* Overflow-x to hidden
* I used TinyPNG to compress the images used on the website

<dl>
  <dt>Hero image</dt>
  <dd>Hero image resizes responsively &#10004;</dd>

  <dt>News links</dt>
  <dd>News cards show an icon on hover, and direct user to relevant section on click. &#10004;</dd>

  <dt>Music rows</dt>
  <dd>Music row images alternate position on desktop &#10004;</dd>
  <dd>Music rows stack in order on mobile &#10004;</dd>

  <dt>Music content</dt>
  <dd>Music content is horizontally and vertically alligned on all screens &#10004;</dd>
 
  <dt>Music buttons</dt>
  <dd>Music buttons jumps slightly on hover &#10004;</dd>
  <dd>Music buttons links open in new tab &#10004;</dd>

  <dt>Video</dt>
  <dd>Video scales for mobile screens &#10004;</dd>

  <dt>Tour table</dt>
  <dd>Buy now text inverts on hover &#10004;</dd>
  <dd>Buy now links open in new tab &#10004;</dd>
  <dd>Table scales responsively &#10004;</dd>

  <dt>Newsletter</dt>
  <dd>User is prompted to enter email &#10004;</dd>
  <dd>Warning appears if user doesn't enter '@' &#10004;</dd>
</dl>


---

## Deployment
* I deployed this website via GitHub Pages. [Link to website](https://andreasdk.github.io/ariana/)
* There are no differences between the local and deployed websites.
* I only used a main branch.

---

## Credit

#### Content
* I got the tour dates from the official Ariana Grande [website](https://www.arianagrande.com/events)
* I got the music links from [Spotify](https://open.spotify.com/artist/66CXWjxzNUsdJxJ2JdwvnR?si=0LIaRBRiQhm99Tt-2SMftA)
* I got the music links from [YouTube](https://www.youtube.com/watch?v=1ekZEVeXwek)
* The Amazon and FNAC links I found by searching on the respective websites
* I also got the social media links through a Google search

#### Images
* [Hero image](https://studybreaks.com/wp-content/uploads/2018/12/dangerous-main.jpg)
The hero image was edited in Photoshop to add a gradient
* [News image 1](https://yt3.ggpht.com/a-/AAuE7mD4NXLs5D8DZpyMe3jQSKtrqLDkoo3W8cOccQ=s900-mo-c-c0xffffffff-rj-k-no)
* [News image 2](https://1.bp.blogspot.com/-nqYI7OqqhGY/WvjClpXrlQI/AAAAAAAC_bw/A_-I2GzVfFsd7NXbhHRzYIWAlk-0qJmDgCLcBGAs/s1600/ARIANA+GRANDE+%2833%29.jpg)
* [News image 3](http://www.mtv.co.uk/sites/default/files/styles/image-w-520-h-520-scale-crop/public/mtv_uk/galleries/large/2018/06/19/ariana_grande_.jpg?itok=TcfLNEZj)
* [thank u next album cover](http://www.jagurltv.com/wp-content/uploads/2019/02/img_6272-1.jpg)
* [sweetener album cover](https://i.redd.it/hah0v10wrv411.jpg)
* [dangerous woman album cover](https://i1.wp.com/www.arianagrandebutera.com/wp-content/uploads/2018/12/Dangerous-Woman-Ariana-Grande.jpg?fit=1400%2C1400&ssl=1)
* [my everything woman album cover](https://i.ebayimg.com/images/i/192823100415-0-1/s-l1000.jpg)

#### Acknowledgements
* I used code from the following [CodePen](https://codepen.io/littlesnippets/pen/vKpvGP/) for my news cards, although modified for this project
* I received inspiration for this project from Cole Steele's Web Developer Bootcamp on Udemy, specifically the layout of the music section
* I used code found on [Stack Overflow](https://stackoverflow.com/questions/23706003/changing-nav-bar-color-after-scrolling) to change the nav-bar background color on scrolling.
* My mentor also helped me out with UX improvement suggestions




