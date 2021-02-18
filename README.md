# Nicola - A Singers Website

## A User-Centric Frontend Milestone Project

This is my first Milestone project with Code Institute and my first ever web design.
I decided to create a website for a famliy member who is a singer along the lines of a suggested project withing the course (Build a website for a band).
The aim of the project is give my neice web pntial employers.resence and show-case her abilities to fans and potential employers.


<!-- One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch.   -->
---
## <u>Table of Contents</u>

- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [User goals](#user-goals)
        - [New Fan Goals](#new-fan-goals)
        - [Returning Fan goals](#returning-fan-goals)
        - [Website owner  goals](#website-owner-goals)
    - [User stories](#user-stories)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
- [Features](#features)
- [Technology Used](#technology-used)
- [Testing](#testing)
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)
    - [Code Validation](#code-validation)
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-found-during-site-development)
    - [Performance testing](#performance-testing)
- [Deployment](#deployment)
- [Credits](#credits)
- [Screenshots](#screenshots)
 
 ---
## <u>UX</u>

 ### User Goals
  
 #### New Fan Goals

I want to find out more about Nicola.

I want to see pictures of Nicola.

I want to be albe to contact Nicola.

I want to be updated on when and where nicola is next performing.

#### Returning Fan Goals

I want to keep upto date on where Nicola is performing.

#### WebSite Owner Goals

I want to have a Web presence so prospecitve employers can find out more about me.

I want to update and inform my fans of my singing and songwriting and any new videos or music I am producing.

I need a place for potential employers to contact me for booking me.

#### User Stories





### Structure of the website

I want the website to be easily accessible, simple to navigate and user freindly. It must also be displayed 
  for various devices (desktop ,Tablet, Mobile Phone) whilst maintaining a great user experience . Links within the website directing me to other Pages either within
  this website or to other social media accounts (youtube etc). I waould like to have effects like hover to bring the website alive and encourages interaction.


### Wireframes

I used Balsamic to create wireframe mockups of how I envisioned the website to look.
These are listed bleow

- wireframes to be added here

---
## <u>Features</u>

As this is a new project the website will consist of 3 pages with view to increase as neccesary (see features left to implement below.)
Home page, Gallery and Contact page.

#### Fonts

- The main font used is 'Kodchasan' with back-up of  sans-serif  obtained from [Google-fonts](www.fonts.google.com)

#### Images

- Most Images are sourced direct from the singers social media.  In time these can be replaced with higher quality images.  The cover picture was created by the singer.

- [unsplash](www.unsplash.com) used for images as well. see [#credits](#credits)

#### Navbar and footer

- Both have same sytling and colors for consitancy. This is reflected across all pages of the website.

- Navbar located at top with 'Brand' to the left and a responsive menu on the right. For Mobile and tablet this is 
  an expanding 'Hamburger' menue opening below the icon to reveal the three pages (Home, Gallery and Contact).
  On desktop the 'hamburger'  is replaced wth links for the 3 pages.  

- Footer is located at the bottom and contains Social media links.

#### Hero Image

- Full size image of the singer that is responsive to device size

#### about-me section

- A brief bio of Nicola

#### Upcoming events.

- A gallery with nicolas upcoming performances, inlcuding dates, time and location.

#### Gallery Page

- Fixed tile gallery of images relating to nicola. Responsive effect when hovering over the pictures. 

#### Contact Page

-  Contains a form for fans or prospective employers to send messages to Nicola

 
### Existing Features

- Content form allows for a message to be sent to the site owner.  This could be for prospective employers to make contact to hire nicola , other singers/bands wishing to collaborate
or Fans to ask questions.

#### Future Features 

- Fully functioning Play/stop button in the header.  

- Gallery pictures curretly enlarge on hoverct on mobile or for desktop, This has no effe tablets. Plan to add a large popout carousel of the images when clicked on.

- a Seperate Video/ music page. 

- Merchandise page 

- incorporate a presskit/review section into the website by either a new page or addition to other.

- A News blog which links to recent performances or live stream events as well as other relevant news.

- Higher quality and relavant Images when they become available.

---
## <u>Technology Used</u>

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
  - Main Programming language

* [CSS](https://en.wikipedia.org/wiki/CSS) 

  - Style sheet language

* [Google Fonts:](https://fonts.google.com/)

  - Used to import custom fonts

* [Font Awsome:](https://www.fontawesome.com) 

  - Used to import icons

* [GitHub:](https://www.github.com.com)

  - Used to store projects created in gitpod. 

* [Gitpod:](https://www.gitpod.io.com)

   - used to develop the project, including version control (using commits and comments.)

* [Bootstrap 4:](https://www.getbootstrap.com)

  - used to assist in a responsive site with a mobile first ethos 

* [Balsamic:](https://www.balsamiq.com)

   - Used to create wirefrme of the project.

* [windows Photo editor](https://www.microsoft.com/en-us/p/photo-editor-for-windows-10/9mzwk7vt6b3g?activetab=pivot:overviewtab)

   - Basic photo editor

---
## <u>Testing</u>

### Functionality testing

Mozilla Browser used to run Gitpod and developer tools used to test , solve problems, style and responsiveness.
Chrome develeper tools used to check compatibility through-out and to check on consistency of mozilla dev tools.

### Compatibility testing

I have tested the website on the virtual devices contained with the Dev Tools of Mozilla and Chrome with no 
issues seen on either. A wide range of screen sizes tested from mobile, tablet and desktop.

I have tested compatability on the github pages published website of the project on a 1920 x 1080 monitor, a galaxy s7 
and a Motorola  one+ mobile phone with no issues noted.

### Code Validation
-  https://jigsaw.w3.org/css-validator/
-  https://validator.w3.org/
### User stories testing

### Issues found during development

Fixed Navbar caused content go underneath. After trying margins and paddings on the divs and sections to solve this to 
no avail I found that using padding-top on the body tag pushed content lower and solved the issue. This led to other issues where 
I then made the navbar a fixed height which caused no background to be displayed on the drop down menu. This was fixed 
by changing to min-height for navbar and therefore making sizing of the navbar predictable and easier.

Initially had a carousel to display the event section, this caused some issues where the page seems to be flicking when the image changed.
This feature didnt look particually good so was removed with advice from the mentor.  

gallery images - adding container- fluid solved issue with borders on left and right. 

gallery image display. column sizes changed for better layout. xl-3 added for full screen viewing. md-3 changed to 4 which is better for i-pad pro. scaling of images better.
They were becoming squashed as too many items being displayed.  I have set media queries for different veiw sizes to 
keep them at the intended sizes.

The contact page had a minor display issue when viewing on small mobile devices. When the contents were moved into block form
the background was showing where it should be the contents box.  Issue resolved by adding 5px to the padding-right.

The Navbar had a particually annoying issue that was limited to Ipad devices where 1px grey horizontal lines were visible in the footer section of all pages
and also inbetween the event heading and event images.  This was solved for me by moving the ' h4 - Upcoming events' onto the top of the box container for 
the events section.  Prior to this it was nested above in its own Div that closed at start of the event images. This coincidently stopped
all the grey lines including them in the footer.




### Performance testing

<!-- In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the si well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
te works
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.
-->

 

---
## <u>Deployment</u>

<!--
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.
-->

---
## <u>Credits</u>

### knowledge base and design ideas

* [getbootstrap.com/docs](https://getbootstrap.com)

* [w3schools.com](https://www.w3schools.com)

* [geeksforgeeks](https://www.geeksforgeeks.org/how-to-change-hamburger-toggler-color-in-bootstrap/) -
changing 'Hamburger' Menu color 

### Code Templates

- Navbar - [Bootstrap](https://getbootstrap.com/docs/4.6/components/navbar/)   
- gallery grid and Event grid - [Startbootstrap](https://startbootstrap.com/snippets/thumbnail-gallery)  
- Contact form -[Bootsnip](https://bootsnipp.com/snippets/qr1zR) 

### Content

Bio/about me. Created by nicola and edited by myself.  

### Media

* Images provided by nicola

* Clickplay photos. Dagenhams got talent. Nicola and rebecca

* [Unsplash](https://www.unsplash.com) - photo 12 in gallery - Photo by Robert Vergeson on Unsplash

### Acknowledgements

Code Institute README and  template from mentor untilized to meet expected criteria.

[Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - Youtube hosted Front end tutorials.

Credit: https://www.geeksforgeeks.org on how to change hamburger menu color

I was inspired by the website of [Erin Wall](http://www.erinwall.com/) which really drew my attention to its structure and layout
 
## <u>Screenshots</u>