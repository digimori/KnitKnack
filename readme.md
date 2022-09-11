# Milestone Project 1 - Knit Knack

### Purpose of this site:
A general, easy to use resource tool for people who want to learn to knit or already might be a knitter, but want some extra patterns or techniques to learn. 

### Developer Goals:
* To make a clean, clear, easy to navigate site that is responsive on multiple screen sizes.

* A professional first pass at making a functional, responsive website using HTML, CSS and the addition of Bootstrap framework.

* To direct users to adequate resources beyond the scope of the basic tutorial video page to further their understanding and abilities in knitting.

* To give some first line inspiration in the patterns section to people looking to learn to knit, or perhaps attempt a more difficult project.


### User Stories:

* I want the user to be able to easily navigate their way through the site, by using a clean and clear navigation bar that sticks to the top of the page for easy finding.
Also through the use of page jump buttons provided, so that they can jump to beginner/intermediate/advanced depending on their preference. 

* To be able to view external links such as the suggested patterns and tutorial videos off site in a new tab.

* The ability to be easily contactable for queries and collaboration requests through the form on the contact page.

* To be able to easily search the site (Hence the search bar being in the header) to find what you need. 


### Design Choices: 

* For most of the pages, I chose to use Bootstrap as it was what I had most recently learned and is a very useful, responsive framework with a lot of built in components that are easily manipulated through CSS. 
However, for the Tutorials page, I chose to slightly challenge myself and not use Bootstrap for it, as I would like to not rely on it as a crutch.

* Fonts: I chose "Raleway" for all of the main headings and then "Roboto Condensed" for the rest of the page text. This was a stylistic choice mostly just because they stood out to me when browsing fonts and I liked how they looked together.

* Colours: I wanted a fairly neutral colour as the primary background (I changed this a few times, going lighter and darker between beige tones until I found one I liked) and a more popping colour without too much in-your-face saturation. 
Purple is the colour I find myself knitting with the most, so that sealed it for me once I found a tone that looked presentable against the beige. 
I used the colour picker in Adobe Photoshop to compare colours until I found ones that matched to my tastes.
The font colour in the heading being white as opposed to the dark grey or beige used on other pages was due to the background being used in the header. 
It blended in far too much with either of those colours and the white didn't look out of place as it matches the Search bar and the card containers on the patterns and contact form pages.

* Styling: I chose rounded corners on the card boxes because it just looks more professional and clean, like you've done something with it rather than just throwing some images on a page and calling it done. 
The white background on the Patterns Card boxes was a stylistic choice based on the fact that many stock photos given by official pattern brands will often have white borders. It just looks generally tidier if you're unsure if you are allowed to alter a stock photo. 

* Images used: I chose stock images from Unsplash (credited in their own section below) and overall chose from the same keywords such as "Knitting", "Knitwear", as it kept the imagery overall consistent. 

# Credits:
Bootstrap CDN (General layout, cards on Patterns page and responsive styling)
W3Schools (Javascript for Sticky-Top on Navigation bar)
StackOverflow (Literally every query I had on why something was breaking)
FontAwesome (Icons in footer, navigation bar, social links and front page)

## Images and Media:
[Unsplash Images](https://unsplash.com/)


## Patterns links and images:
[Lovecrafts](https:www.lovecrafts.com)

## Youtube videos (Tutorial page):
* [Sheep and Stitch](https://www.youtube.com/c/sheepandstitch)
* [Wool and the Gang](https://www.youtube.com/c/woolandthegang)
* [Nimble Needles](https://www.youtube.com/c/NimbleNeedles)

# Code
* Bootstrap CDN for the general layout and responsive styling such as the inbuilt card objects:

[Bootstrap Cards](https://getbootstrap.com/docs/5.2/components/card/)

[Bootstrap Grids](https://getbootstrap.com/docs/5.2/layout/grid/)

 [StackOverflow](https://stackoverflow.com/) for queries if something was breaking, typically display: inline/block problems I was having. 

 W3Schools for the JavaScript used to sticky the Navigation bar to the top of the page:
[Javascript Code here](https://www.w3schools.com/howto/howto_js_navbar_sticky.asp)

 FontAwesome and the other one for icons used throughout the navigation bars, reasons for knitting headersand footer 
* [FontAwesome](https://fontawesome.com/)
* [RemixIcon](https://github.com/Remix-Design/RemixIcon)

* iframe embed codes taken directly from the youtube embeds themselves and later altered to meet validation requirements (as some code in their default embed such as frameborder do not pass validation).

* Fonts - [Googlefonts](https://fonts.google.com/)

* Other general knowledge from the [CodeInstitute](https://learn.codeinstitute.net/ci_program/diplomainwebappdevelopment) course and from [Codecademy](https://www.codecademy.com/) (I have a Pro account).


# Wireframes
* [Homepage Wireframe](assets/wireframes/homepage.png) 
* [Patterns Page](assets/wireframes/patternspage.png)
* [Tutorial Page](assets/wireframes/howtopage.png)
* [Contact Page](assets/wireframes/contactpage.png)

As you can see some changes have been made along the way after some pointers from my mentor such as the sticky topped navigation and removal of the search bar.


# Testing and Validation
* Tested thoroughly through Google Devtools using varying page breakpoints and element selection on the "Inspect Element"
* Tested responsiveness across several devices built into the Inspect Element tool
* Validated through both [HTML Validator](https://validator.w3.org/) and [CSS Validator](https://jigsaw.w3.org/css-validator/)

## Bugs and fixes:
* Changed the page jump buttons from using the -button- code and instead implemented a form as nesting a button inside of an anchor tag was causing it to throw a fatal error in validation.
- This change was suggested to me by a friend who is also a front-end developer.

* Initially the iframes were not sitting central on the page and were constantly veering off to the left. This was fixed by playing with the margins in Chrome Devtools until it centered. I then copied the code from Devtools and implemented it into my actual code.

* Removed the Search bar as it was not hooked up to the backend yet and therefore not a functional part of the site.

* Altered the Z-index and contrast of the header as it was throwing up some contrast issues on chrome dev tools. 

* Media queried the cards on the patterns page as they were overlapping at certain breakpoints. 

### Other Validation changes:
* Removed excess DIV tags that I had put in once they were pointed out by thge validator tool.
* Added "Noopener" and "Nofollow" to all external links at the advice of my mentor.
* Changed SPAN classes to div containers as I would have been otherwise unable to use header tags within them. 

## Deployment
Deployed site through Github pages [over here](https://digimori.github.io/KnitKnack/).


### To deploy and run locally: 
* Create a [Github account](https://github.com/).
* Use the Chrome browser
* Download and install the Gitpod browser extension for Google Chrome.
* Restart browser after installation has completed.
* Log into Gitpod using your Github username and password.
* Navigate into your desired Gitpod repository
* Click the green "Gitpod" button on the top right of the repository file section.
* This will open the project into a Gitpod workspace and can then be worked on in a local setting.

### To deploy and run project on a local IDE:
* Follow [This Link](https://github.com/digimori/KnitKnack) back to the Github project respository.
* Select the menu item above the repository files labelled "Code".
* To clone: Select the appropriate url or open to Git Desktop.
* To view on a web IDE: Click the dropdown "Open in Web IDE" and choose the appropriate IDE. This dropdown can also be used to clone the code into VSCode IDE.
* To clone into the Local IDE - in the terminal, type 'git clone' followed by the URL that can be copied from the aforementioned Code URL.

## This deployment tutorial was reimplemented from the video on CodeInstitute on how to deploy your project and write a README.


### Deployment issue fix:
Navigation links were prefaced with /, ie: "/contact.html" and I realised that this is telling the directory to go up a level, so the pages were not linking on Github pages. This has since been removed and fixed, so it now functions as intended.