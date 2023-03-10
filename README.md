# The Greenbank Pub Website
![wesbite preview](/assets/img/readme/res-design-screen.png)

## Welcome to the Greenbank Pub!

This project was created for my first milestone project with code institutes Level 5 Diploma in Web Application Development. I have chosen to create this fiction website since I actually personally work at this pub and thought it would be a good base for my first project- as well as lending to ample individuals to test and gain feedback from. 

## [Visit the Greenbank live website here](https://beng-brown.github.io/the-greenbank-pub/)

<br>

# Contents 

### [User Experience](#user-experience)
- [Purpose](#purpose)
- [User Stories](#user-stories)

### [Design](#design-1) 
- [Color Scheme](#colour-scheme) 
- [Fonts](#fonts) 
- [Wireframes & Structure](#wireframes-and-structure) 

### [Features](#features-1) 
- [Home Page](#home-page)
- [Food & Drink](#food--drinks-page)
- [Booking Page](#booking-page)

### [Technologies](#technologies-1)
- [Languages](#languages)
- [Tools](#tools)

### [Testing](#testing-1)

- [User Story Testing](#user-story-testing)
- [Links & Functions](#links-and-functions)
- [Browser testing](#browser-testing)
- [Lighthouse](#lighthouse)
- [Improvements/Bug Fixes](#improvementsbug-fixes)
- [Validator Testing](#validator-testing)

### [Deployment](#deployment-1)

### [Credits](#credits-1)
- [Media & Content](#media--content)
- [Code](#code)
- [Acknowledgments](#acknowledgments)

<br>

---

<br>


# User Experience

## Purpose

This website is for the Greenbank Pub- I have set out to create an easily navigated website built with the purpose of advertising to new potential customers and offering more information on people wanting to visit and book into the establishment. 
 
 This website is aimed at a large general audience to offer easily obtained information on our opening times, food and drinks offerings etc. As well as giving the option to contact us in regards to bookings or other enquires. With the aim of making the requesting more information and booking process and quick and painless as possible. 

 The plan was to make the site as easily navigable and understandable for people of all ages and walks of life. The design of the site reflects this with keeping it simple yet visually attractive.

 ## User Stories

 ### Client Goals

- To be immediately obvious that this is a hospitality business- with the name and relevant pictures this is immediately apparent.
- To traffic more trade to the venue in the way of bookings. Offering a simple form to make a reservations/ask for more info.
-To be responsive and able to view on all devices.
- simple navigation and access to food/drink menus. 
- Contact details and where to find us as well as social media links.

 ### First time Visitor Goals

 - I want to find out the location of the pub and its opening hours for drinks and food.
 - I want to be able to see the menus to make sure I want to eat/drink there.
 - I want to gain a sense of what the pub is like through attractive pictures of the place its self and its offerings.
 - lastly I would like to book a table simply and quickly. 

 ### Second Time Visitor Goals

 - I would like access to the recent menus and opening times etc in case anything has changed.
 - I would like to be able to book a table quick and easily.
 - I would like to be able to be able to find easily contact information for any further questions I may have.

 ### Multiple Visitor Goals

 - I would like to access the menus.
 - I would like to book a table.
 
<br>

# Design

## Colour Scheme

I created a palette using the site 	[Coolers ](https://coolors.co/). I choose to go with a Green theme for obvious reasons. Creating a nice earthy, soothing colors which also offered great contrast. Ideal for highlighting headers, defining sections and other important information.  

<br>

<img src="assets/img/readme/coolers-pallete.png">
 
 <br>

## Fonts

I used [Google Fonts](https://fonts.google.com/) for my webpage fonts. I settled with 'Inter' I really liked this font it was nice and readable for accessability reasons. It also came with a range of weights, which ment after some playing around I only needed the one font. With the added weight it gave great contrast between headers and areas of text. I feel it complimented site really well. I also used the back up as san-serif.

## Wireframes and Structure

I used [Figma](https://www.figma.com/) to create some previews of what I envisioned my site to look like. This was a great tool, as even though my finished project does stray slightly to the original plan, Fimga allowed me to already have my fonts, color schemes and general layout of the site ready to code. This being my first project benefited my enormously. 
<br>

### Wireframe screenshots:
<details><summary>Desktop</summary>
<img src="assets/img/readme/desktop-figma.png">
</details>

<details><summary>Mobile</summary>
<img src="assets/img/readme/mobile-figma.png">
</details>
<br>
As you can see, during the coding process I created another page and moved the food & drink section over. I chose to do this as  felt the page was slightly congested and it made room for a small gallery on the index page.

The sites structure comprises of 

- A Home page
- Food & Drinks page
- Booking Page

## Features

**ALL** the pages contain the same header and footer. And follow the same pattern of having a hero image placed just below. There are also alternative links throughout the pages offering the visiter to continue their journey through the site without having to scroll back to the top. There is also a small "back to the top button" on each page to add to better user experience.

The suggested journey would be Index > Food & Drink > Booking. 

<br>

**Header**- The header comprises of two parts 1) being the logo which I created myself using figma and then exporting it. 2) Being the navigation links on the opposite side. Giving a simple but smart appearance. 

As shown below in desktop and then mobile sized screens. On smaller screens the navigation links shift to beneath the logo. Allowing for greater ascetics, user experience and showing responsive design.  

<img src="assets/img/readme/header-example-desktop.png">
<img src="assets/img/readme/header-example-mobile.png">

<br>

**Footer**- The footer also follows a similar template however instead of a logo there is the address and the contact details of the venue. Followed on the other side by social media links. 

Similarly to the header this also folds when on smaller screen sizes. For the same reasons as above. 

<br>

<img src="assets/img/readme/footer-example-desktop.png">
<img src="assets/img/readme/footer-example-mobile.png">

<br>

### Home Page

The home page comprises of 3 sections the first being a hero image followed by an "about" paragraph giving a brief background on the pub. We then have a gallery consisting of 6 images & finally followed by a section about our customer loyalty scheme inc a sign up form and our pub/kitchen opening times.

All pictures and text have been carefully placed and picked so that it is obvious that this page is for a pub/restaurant.

### Food & Drinks Page
The food & Drink page also follows in a similar manner, having a large hero img and some text about what we offer. 

Beneath this we have our menu section. With links to the PDF menu tied to the pictures. These also scale 1:2 when hovered over, which is a nice touch to draw attention. However this wouldn't work with mobile sizes and would offer a poor UX as shown below it is coded to be responsive and take up less space. The hover is ignored and the text bos is hidden-on smaller screens.
<details><summary>Menus on Desktop</summary>
<img src="assets/img/readme/menus-desktop.png">
</details>

<details><summary>Menus on Mobile</summary>
<img src="assets/img/readme/menus-mobile.png">
</details>

<br>

### Booking Page

The booking page comprises of a large booking form beneath text about options in regards to booking, private function/table reservations etc. 
This is followed by 4 responsive reviews and an iframe containing a google map of where the Greenbank Pub is situated. 

<details><summary>Booking Form</summary>
<img src="assets/img/readme/booking-form.png">
</details>

<details><summary>iframe/reviews section</summary>
<img src="assets/img/readme/iframe-reviews.png">
</details>
<br>

### Future Additional Features

One main thing I would love to add in the future when I have further developed throughout this course would be a fully functional take away menu along with an interactive and updatable events/whats on listing page. 

# Technologies 

## Languages
CSS & HTML 

## Tools

- [Github](https://github.com)- Storing and hosting my code
- [Gitpod](https://www.gitpod.io/)- Code Editor, create, edit and preview my code
-  [Git]()- Used for version control
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)- Used to test responsiveness on different screens & layout etc
- [Figma](https://www.figma.com/)- Used to create and develop my previews inc fonts, colors, images etc
- [Fontawsome](https://fontawesome.com/)- Sourced my icons, including the social media in footer
- [Hover.css](https://ianlunn.github.io/Hover/)- Database of CSS3 powered hover effects to be applied to links, buttons
- [Cooleors](https://coolors.co/)- Used to create and pick my color scheme
- [Pexels](https://www.pexels.com/)- Stock images used throughout my project
- [Am I Responsive](https://ui.dev/amiresponsive)- To create a preview of my website across different devices
- [W3C CSS Validation Service](https://validator.w3.org/)-  Online validator used to validate my CSS code
- [W3C Markup Validation Service](https://jigsaw.w3.org/css-validator/)- Online validator used to validate my HTML code
- [Color Contrast Accessibility Validator](https://color.a11y.com/Contrast/)- Used to check the color scheme in regards to contrast of fonts and background colors. 

<br>

# Testing

## User Story Testing 

<br>

| **First Time Visitor Goals** | **Solution** | **Outcome** |
| ---| ---| ---|
|Gain a sense of what the pub is like through attractive pictures of the place its self and its offerings | First thing you are drawn to on the home page is the logo, large hero image & "about" text giving a sense of what the pub and the page is about. | Achieved |
| Easily visible and direct route to the online Menus and opening hours| Several ways, the nav bar on top of every page has a link named "food & Drink" providing an immediate route to the section. There is also another button placed just after the home page gallery named "check out our menus" | Achieved|
| Opening hours and address easily identified| The opening hours can be found near the bottom of both the home & food pages. The address and other contact details can be found in the footer on every page. There is also an Iframe containing google maps directions | Achieved|
| Navigate to and easily book a table/function | On the nav bar present on each page there is a clearly marked "booking" link which will take you directly to our booking page containing the form, there is also another button placed on both the home and food pages "want to make a booking" to save scrolling back to the top and creating a better and more direct user experience | Achieved |

<br>

| **Multiple Time Visitor Goals** | **Solution** | **Outcome** |
| ---| ---| ---|
|Access to the recent menus and opening times etc in case anything has changed| On the nav bar present on each page there is a clearly marked "food & Drink" link which will take you directly to our booking page containing the menus, providing simple andefficientt access to the information you want. | Achieved |
|I would like to be able to book a table quick and easily| Similarly to the above the "booking" link is at the top of every page creating a direct link straight to the booking page. | Achieved |
| Enticed to Links of our social media, for more regular goings on & increase pub interaction/ following | On the footer of each page I have used font awesome icons to make clear and unmissable links to our socials. | Achieved |

<br>


## User Story Summary

Overall this website is easily navigated for both the first time and multiple visitors. With clear and obvious links taking the user directly to were they need to go. Or a slightly more meandering route for the first time visitor who would be looking for more information about the establishment. 

The client goals were to make this stand out as a friendly hospitality venue, through the use and placement of images, logos and text this has been achieved. With several links and prompts throughout the page urging the user to continue and view our menus followed by the booking page. increasing traffic and hopefully bookings. 

This site is responsive on all sized devices.

## Links and Functions
<br>

| **Page** | **Testing** | **Outcome** |
| ---| ---| ---|
|All| Nav links go to the correct page/location| YES|
|All| Logo links back to the home page| YES|
|All| Social Media links to relevant platforms| YES|
|All| Everything is responsive to device sizes| YES|
|HOME| Loyalty Sign-ip form works as intended |YES|
|BOOKING| Booking form works as intended- Required fields|YES|
|FOOD & DRINK| Menu links to relevant PDF |YES|

<br>

## Browser Testing

I have tested this site on Chrome, Mozilla, Edge & Safari (mobile.) I have tested the responsiveness using the screen device size on devtools and also checked all links and images are displaying and working.  

## Lighthouse
<details><summary>Desktop results shown below, Order: Index > Food & Drink > Booking</summary>


<img src="assets/img/readme/desktop-dev.png">
</details>

<details><summary>Mobile results shown below, Order: Index > Food & Drink > Booking </summary>
<img src="assets/img/readme/mobile-dev-before.png">
</details>
<br>

## Improvements/Bug Fixes

As seen on the mobile results the performance can be better, as suggested by DevTools I converted all my images from jpeg to webp. Reducing the file size and lessing the loading times. 

<details><summary>Updated results- Once Changing img files</summary>
<img src="assets/img/readme/mobile-dev-after.png">
</details>
<br>

As you can see "best Practices" also isn't 100% this is as my main logo isn't big enough and is being stretched when moving down to smaller devices, i fixed this by making a new logo-same design but double the size in width/height and applying a max width code to re-size it down. Preventing any pixilation.

<details><summary>Final results Desktop/Mobile</summary>
<img src="assets/img/readme/final-devs.png">
</details>
<br>

As you can see as a result of these fixes it has boosted both the desktop and the mobile results.  

I made an adjustment to all the forms in the way of inserting a pattern input on the "phone number". This stopped the issue of someone placing letters. I also set a "min", "max" figure of 1 & 99 respectively in the booking form "Guest Count". This all added to the functionality of the webpage.

Finally I added a new media query into the 400px break point. Boosting the size of the sign up form to 80%. was a little small and now looks far more visibly appealing. 

## Validator Testing 

HTML
<details><summary>Results No-issues</summary>
<img src="assets/img/readme/html-validator.png">
</details>
<br>

CSS
<details><summary>Results No-issues</summary>
<img src="assets/img/readme/css-validation.png">
</details>
<br>

Color
<details><summary>Results-No issues</summary>
<img src="assets/img/readme/color-validator.png">
</details>
<br>

# Deployment

These are the steps that I to deploy my site on GitHub pages.

- Log into GitHub account
- Head to the project repository
- Click on the "settings" tab near the top right of the page
- Then to "pages" on the setting menu-left hand side
- Source select "deploy from a branch"
- Branch select "main" & "root"
- Hit save
- May have to wait a few minutes- the site is then live!

<img src="assets/img/readme/site-deployment.png">

# Credits

## Media & Content

- The images that used throughout my site were all sourced from [Pexils](https://www.pexels.com/)
- The Logo way made myself however it is based loosely on the actually Greenbank Pub logo (permission received)
- The menu PDFs are sourced from the original live [Greenbank website](https://www.thegreenbankbristol.co.uk/), although this is a fictional site I have all the required permission from the Pub itself.
- The content in the "welcome/Food/Booking" sections has been biased on the original site- adapted and built upon by myself. 


## Code

- [Ian lunn-github](https://ianlunn.github.io/Hover/) for button hover effects
- [font awsome](https://fontawesome.com/) for the icons used
- General coding niggles helped by [W3School](https://www.w3schools.com/)
- [Kevin Powel-Learn flexbox](https://youtu.be/u044iM9xsWU) youtube video
-  Code institute "love running"- Loosely based my "reviews" section on their "time" section. 



# Acknowledgments

Special thanks to my Tutor- Pasquale & Mentor-Jack for their help and guidance throughout this project. As well as staff at the Greenbank Pub for being the site guinea pigs and for their constant feedback throughout the project. 