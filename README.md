# The Unofficial TEKKEN Rundown

[The Unofficial TEKKEN Rundown website](https://andreeeasn.github.io/pp1-tekken-rundown/) was developed both to shed some light on the long-lasting history of the TEKKEN franchise and potentially attract some new players to the scene.
The user can scroll through a gallery of mainline TEKKEN games released over the years as well as some interesting spin-off titles featuring TEKKEN characters. 
The user may also read through the Beginner's Guide for a push in the right direction should they be willing to learn more about playing the game, as well as sign up for a newsletter regarding new TEKKEN releases, large tournament events and developer commentary.

![Responsive Mockup](assets/images/documentation/am-i-responsive.png)

# Table of Contents
+ [UX](#ux "UX")
  + [User Demographic](#user-demographic "User Demographic")
+ [Features](#features "Features")
  + [Navigation Bar](#navigation-bar "Navigation Bar")
  + [Hero Images](#hero-images "Hero Images")
  + [About TEKKEN Page](#about-tekken-page "About TEKKEN Page")
  + [Mainline Games Page](#mainline-games-page "Mainline Games Page")
  + [Spin-off Games Page](#spin-off-games-page "Spin-off Games Page")
  + [Beginner's Guide Page](#beginners-guide-page "Beginner's Guide Page")
  + [Newsletter Sign-Up Page](#newsletter-sign-up-page "Newsletter Sign-Up Page")
  + [Footer](#footer "Footer")
+ [Testing](#Testing "Testing")
  + [Validator Testing](#validator-testing "Validator Testing")
  + [Bugs Encountered](#bugs-encountered "Bugs Encountered")
+ [Media](#media "Media")
+ [Credits](#credits "Credits")

## UX

### User Demographic

This website was designed for:
  - Users interested in the background of the TEKKEN franchise wanting to know more
  - New players that have yet to begin playing due to the steep learning curve
  - Intermediate players wanting to brush up on their fighting game knowledge
  - Veteran players curious about the past entries of the series or wanting to receive news on upcoming content/events

### Design

#### Color Palette

  - The header background is the #bc0e0e, a shade of red inspired by the TEKKEN 7 Cover Art.<br>
    ![TEKKEN 7 Cover Art](assets/images/documentation/tekken-7-cover.png)<br>
  - The background color for each page is influenced by their hero image.<br>
    All varying degrees of blue but shifted towards other colors to match their respective hero image, adhering to a gradient generated using ColorSpace.<br>
  ![Color Palette](assets/images/documentation/colorspace-gradients.png)

## Wireframes
  - About TEKKEN Page:<br> 
  ![About TEKKEN Page](assets/images/documentation/wireframe-index.png)
  - Mainline Games Page:<br> 
  ![Mainline Games Page](assets/images/documentation/wireframe-games.png)
  - Spin-off Games Page:<br> 
  ![Spin-off Games Page](assets/images/documentation/wireframe-spinoffs.png)
  - Beginner's Guide Page:<br> 
  ![Beginner's Guide](assets/images/documentation/wireframe-beginners-guide.png)
  - Newsletter Sign-Up Page:<br> 
  ![Newsletter Sign-Up Page](assets/images/documentation/wireframe-signup.png)<br>
While taking a few artistic liberties, the finished project mirrors the original intent fairly well.

## Features 

### Navigation Bar

  - Featured on all pages, allows the user to navigate freely between the 5 pages available:
    - About TEKKEN
    - Mainline games
    - Spin-offs
    - Beginner's Guide
    - Newsletter
  - The current page is highlighted on the navigation bar to quickly allow the user to see what page they're on.
  - The navigation bar will remain static on top of the screen, allowing the user to reach it from anywhere on the page.<br>
    ![Nav Bar](assets/images/documentation/navbar.png)
  - On smaller screens the navigation links will be replaced with a menu button that opens a vertical navigation menu.<br>
  ![Mobile Nav Bar Closed](assets/images/documentation/navbar-mobile-closed.png)<br>
  ![Mobile Nav Bar Open](assets/images/documentation/navbar-mobile-open.png)

### Hero Images
Each page has it's own hero image featuring the various stages present in TEKKEN 7. 
  - About TEKKEN Page:
  ![About Tekken Hero Image](assets/images/tekken-hero-image-1.jpg)
  - Mainline games Page:
  ![Mainline games Hero Image](assets/images/tekken-hero-image-2.jpg)
  - Spinoff games Page:
  ![Spinoff games Hero Image](assets/images/tekken-hero-image-3.jpg)
  - Beginner's Guide Page:
  ![Beginner's Guide Hero Image](assets/images/tekken-hero-image-4.jpg)
  - Newsletter Page:
  ![Newsletter Hero Image](assets/images/tekken-hero-image-5.jpg)

### About TEKKEN Page

  - The About TEKKEN Page serves as a landing page for users, giving a quick summary of what the TEKKEN franchise is.
  - The About section features a video trailer of TEKKEN 8, the newest installment in the series.<br>
  ![About Page](assets/images/documentation/about-page.png/)
  - Further down on the page is a TEKKEN World Tour Promo, featuring the TWT 2022 logo as well as a trailer.<br>
  ![TEKKEN World Tour Promo](assets/images/documentation/about-page-twt.png)
  - The Promo also features a summary of the TEKKEN World Tour and a link leading to the official Bandai Namco E-sports portal.

### Mainline Games Page

  - The Mainline Games Page functions as a gallery showing off all the official TEKKEN game releases over the years.<br>
  ![Mainline Games Page](assets/images/documentation/mainline-games-page.png)<br>
  The image above showcases the top and bottom of the Mainline Games Page.
  - As the user scrolls through the gallery the background color will have a slight hue-shift towards blue (The same blue featured in the About TEKKEN Page)
  - Among the details listed are release date, platforms released on and what the game did differently from the other entries in the series.
  - Every game also features it's official logo on the left/right, each entry alternating which side displays the art.
  

### Spin-off Games Page

  - A follow-up to the Mainline Games page, featuring spin-off titles instead.<br>
  ![Spin-off Games Page](assets/images/documentation/spinoff-games-page.png)<br>
  The image above showcases the top and bottom of the Spin-off Games Page.
  - As the user scrolls through the gallery the background color shift hues towards purple (The same purple used in the Mainline Games Page)
  - Release dates, platforms and official art are also displayed, similar to the Mainline Games Page
  - Every game also features it's official logo on the left/right, each entry alternating which side displays the art.

### Beginner's Guide Page

  - A fairly lenghty page to guide new players in the right direction should they find interest in playing.<br>
  ![Beginner's Guide Page](assets/images/documentation/beginners-guide-page.png)
  - Features tables on input notations, basic movement and advanced directional inputs.
  - Also features some informational videos on choosing your character, TEKKEN movement techniques and general fighting game concepts.

### Newsletter Sign-Up Page

  - A sign-up form for the Unofficial TEKKEN Rundown Newsletter
  ![Newsletter Page](assets/images/documentation/newsletter-page.png)
  - The user is prompted to enter name, e-mail and region and may then select from 4 additional mailing lists:
    - Upcoming Tekken DLC
    - Tekken World Tour
    - Nearby local tournaments
    - Developer commentary
  - NOTICE - As the Code Institute Formdump page has been down for the last few weeks, submitting the form will not work as of now.
  
### Footer

  - The footer is split into three parts: 
    - Disclaimer that TEKKEN belongs to Bandai Namco
    - Statement that this website was created as a portfolio project
    - Links to the creator's LinkedIn and GitHub<br>
   
   ![Footer](assets/images/documentation/footer.png)
  - The footer is entirely responsive and resizes well to smaller screens<br>
   
   ![Footer On Small Screens](assets/images/documentation/footer-mobile.png)

## Development and Deployment

### Migrating to Visual Studio Code
While GitPod was originally chosen, Visual Studio Code was instead used as the primary development environment for this project as Code Institute has begun moving away from using GitPod. <br>
The GitPod environment was built using the [Code Institute Template](https://github.com/Code-Institute-Org/gitpod-full-template), and later adopted into Visual Studio using the following steps:

  1. Open Visual Studio Code
  2. Select "Clone Git Repository"
  3. Enter the URL of your project repository and click "Clone Repository"
  4. When prompted, select a directory to place your project in and then "Select as Repository Destination"
  5. You may now open the project by selecting "Open Folder" and selecting your chosen directory

### GitHub Pages
The project was deployed to GitHub Pages (Link [here](https://andreeeasn.github.io/pp1-tekken-rundown/)) using the following steps:
  1. Log in to GitHub and locate your project repository
  2. At the top of the repository, select the "Settings" option from the menu
  3. Find the "Pages" option in the list of settings
  4. Find the "Branch" option and select your desired branch ("None" by default, set to "Main") and root ("/(root)" by default)
  5. Select "Save" and your page will be deployed to GitHub Pages
  6. Refresh the page and you should be presented with "Your site is live at: (LINK)" at the top of the page

If the link doesn't appear after refreshing your page, wait for a few minutes before trying again

## Testing

### Links
  - Every link on the navigation bar has been tested from every page and lead to where they're supposed to.
  - Links from the mobile version of the navigation bar have proven to work from every page as well.
  - External links (Bandai Namco E-sports portal on About TEKKEN page and GitHub/LinkedIn links on every page footer) all open in a separate tab upon being clicked. 

### Validator Testing
  - HTML
    - No errors were returned when testing all the pages through the [W3C HTML Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fandreeeasn.github.io%2Fpp1-tekken-rundown%2Findex.html) <br>
  ![W3C HTML Validator Results](assets/images/documentation/w3c-html-valid.png)
  - CSS
    - No errors were returned when testing style.css through the [W3C CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fandreeeasn.github.io%2Fpp1-tekken-rundown%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)<br>
    ![W3C CSS Validator Results](assets/images/documentation/w3c-css-valid.png)
  - Lighthouse Audit<br>
  ![Lighthouse Audit](assets/images/documentation/lighthouse-audit.png)

### Bugs Encountered
  - (RESOLVED) The navigation bar menu button not hiding on larger screens when using firefox
    - The CSS tag content-visibility lacks browser compatibility with firefox and safari. Hiding elements with the simpler display: none; fixed the issue.
  
  - (RESOLVED) Right hand part of screen being cut off at lower screen widths on Beginner's Guide page
    - The headers above the notation tables were unable to break to a new line and as such stuck out of the container, this was fixed by adding style word-break: break-word; to the table.
    - There was also the phrase "strengths/weaknesses" in a paragraph that counted as one very large word not allowing the container to resize properly at very small screen sizes, adding a space inbetween the words ("strengths / weaknesses") solved the issue
  
  - (RESOLVED) Inability to resize youtube videos in their video container
    - Wrapped the video container in a new "video padding" div, allowing change of padding to control size when needed.

  - (RESOLVED) GitHub and LinkedIn links in footer being pushed beneath the padding
    - Replaced the convoluted floated divs in the footer with a simple unordered list with display:flex; to line the 3 objects up in a lot cleaner fashion.
  
## Media
Fonts Used:
  - [Tarrget - by Iconian Fonts](https://www.fontspace.com/tarrget-font-f32924), used in the creation of the Unofficial TEKKEN Rundown logo, based on the TEKKEN Tag Tournament logo font. 
  - [Open Sans](https://fonts.google.com/specimen/Open+Sans), used for headers, closely resembles the font used in the TEKKEN 7 Main Menu.
  
Images used:
  - The README presentation image was taken from [Am I Responsive?](https://ui.dev/amiresponsive)
  - All hero images are in-game captures of TEKKEN 7 (Owned by Bandai Namco), taken using Nvidia GeForce Experience Photo Mode.
  - Logos for mainline games 1-7 and icons for input notations are from the Gallery included in the official TEKKEN 7 release.
  - The TEKKEN 8 and TEKKEN World Tour logos used are from the [Official Bandai Namco Website](https://en.bandainamcoent.eu/tekken).

Videos used: 
  - [TEKKEN 8 Trailer](https://youtu.be/jGQBmSsunT4) & [TEKKEN World Tour 2022 trailer](https://youtu.be/_32qDPgfn6Y) from the official Bandai Namco Entertainment Youtube channels
  - [The Korean Backdash](https://youtu.be/dzIfubaQLyk), [Why Button Mashing Doesn't Work](https://youtu.be/riGCdE6ZPck) and [Why Button Mashing Works (Sometimes)](https://youtu.be/b2wX4EiD5tg) are all from @Core-A Gaming on youtube.

## Credits

Resources and tutorials used for developing this project:
  - [w3cschools.com - How to Create a Sticky Navbar](https://www.w3schools.com/howto/howto_js_navbar_sticky.asp)
  - [w3cschools.com - HTML Tables](https://www.w3schools.com/html/html_tables.asp)
  - [webdevetc.com - How to add a gradient overlay to a background](https://webdevetc.com/blog/how-to-add-a-gradient-overlay-to-a-background-image-using-just-css-and-html/)
  - [css-tricks.com - Three CSS Alternatives to JavaScript Navigation](https://css-tricks.com/three-css-alternatives-to-javascript-navigation/#aa-alternative-3-the-css-only-hamburger-menu)<br> 
  This project uses edited CSS code from this tutorial in particular (Alternative 3: The CSS-only hamburger menu, written by Blake Lundquist) to create a mobile navigation menu without resorting to javascript.
  - Most information regarding release dates, platforms and content from previous TEKKEN installments came from the [TEKKEN Wiki](https://tekken.fandom.com/wiki/Tekken_Wiki).

Big thanks to my Code Institute mentor, [Lauren-Nicole Popich](https://www.linkedin.com/in/lauren-nicole-popich-1ab87539/) for helping push the project in the right direction.