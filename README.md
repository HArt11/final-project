# Arthur's Pharmacy

This website was created for the required Milestone Project One for the Code Institutes Web Development Course using Bootstrap template "Freelancer"

The live website can be found [here](https://hart11.github.io/final-project/)

I wanted to build a website for my own fictional pharmacy. The design is a simple and effective one page scrolling site with internal links to sections, with a contact form for users to get in touch with enquires. 
Important to be aware that all pharmacies are registered with the General Pharmaceutical Council and require a registration logo with registration number. This has NOT been included. 

<br><br>

## Arthur's Pharmacy Overview
***
The site provides interactive modals demonstrating the services this fictional pharmacy can provide. Brightly coloured of images lure the user in. The site would allow a user to sign up to arrange prescription delivery, or wish to find out more information. This is done through a contact form.
The target audience is the younger generation of pharmacy users, with links to a fictional presence on social media, by dipping into and expanding on the usual pharmacy role of prescriptions by offering aesthetic treatments such as fillers. 

<br><br>

Responsiveness has been tested on https://ui.dev/amiresponsive, different mobile devices and using the developer tools from Chrome. It did look when using the Chrome developer tools, that the header image did not fit to page. This doesn't appear to be the case on the actual devices. 

![Am I Responsive image of how the landing page looks across different browser sizes](assets/images/responsive.png) 
<br>

## Table of Contents
* [Project Research](#project-research)
* [User Experience Design (UX)](#User-Experience-Design)
  * [User stories](#User-Stories)
    * [First Time Visitor Goals](#First-Time-Visitor-Goals)
    * [Returning Visitor Goals](#Returning-Visitor-Goals)
    * [Frequent User Goals](#Frequent-Visitor-Goals)
  * [Features](#Features)
    * [Existing Features](#Existing-Features)
    * [Navigation Bar](#navigation-bar)
    * [The Home Page](#the-home-page)
    * [Image Gallery](#image-gallery)
    * [Waiting list application page](#waiting-list-application-page)
    * [Website Footer](#website-footer)
    * [Form Acknowledgement Page](#form-acknowledgement-page)
    * [404 Error Page](#404-error-page)
    * [Future Features](#future-features)
  * [Design](#Design)
    * [Colour Scheme](#Colour-Scheme)
    * [Typography](#Typography)
    * [Imagery](#Imagery)
    * [Wireframes](#Wireframes)
* [Technologies](#Technologies)
* [Test Strategy](#test-strategy)
    * [User Stories Testing](#user-stories-testing)
    * [Manual Testing](#manual-testing)
    * [Accessibility Testing](#accessibilty-testing)
    * [Feedback from User Testing](#feedback-from-user-testing)
    * [Validator Testing](#validator-testing)
    * [Unfixed Bugs](#unfixed-bugs)
* [Deployment](#Deployment)
* [Credits](#Credits)
  * [Code](#Code)
  * [Content](#Content)
<br><br>

## Project Research 
***
As a pharmacist, I've found some of the larger pharmacy chains to have busy websites with adverts selling produtcs. The idea of this website was to strip this back to what healthcare services a pharmacy can provide. 
<br><br>

 ### Research Analysis
  ***
Pharmacy services are changing, and targetting the younger users would prefer to visit a bright, fun and interactive site. Especially with a contact form on to find out more information.
<br><br>

## User Experience Design
***
## User stories
<br>

#### First Time Visitor Goals

- As a First Time user, I want to easily understand the main purpose of the site and learn more about this fictional pharmacy.
- As a First Time user, I want to be able to navigate throughout the site pages to find relevant content.
- As a First Time user, I want to view the website and content clearly on the device I am currently using and switch between devices and have the webpage be responsive.

### Returning Visitor Goals

- As a Returning user, I want to contact the pharmacy to arrange prescriptions or another service.
- As a Returning user, I may want follow them on social media.

### Frequent Visitor Goals

- As a Frequent user, I want to send another message to the pharmacy.
- As a Frequent user, I may want to arrange another service.

<br><br>

 ## Features
 ***
 ## Existing Features 

<Br>

 * ### Navigation Bar
***
![Navbar](assets/images/navbars.png)
<br><br>

 * The navigation bar is present across the main page, and on the message response page. The message response page does not have the dropdown menu, but a user can return to the home page (index.html) by either clicking on the Arthur's Pharmacy logo, or the "Return to Homepage" underneath the thank you message. 
  The nav bar is fully responsive, and a burger menu appears when device size is reduced.
  There has been little styling added to the default navigation menu from the template. The colour choice provides a good contrast with the rest of the page. It does however now include a mortar and pestle Font Awesome icon, and uppercase was removed.
  The options were kept simple and clear, with links to internal markers on the main page.
  - Nav 1 shows the nav-bar of the standard bar as displayed on a desktop.
  - Nav 2 show the bar drop down menu from the burger menu on smaller screens.
  - Nav 3 shows the nav-bar as displayed on the message response page, which intentionally does not contain the burger menu drop down.
<br><br>

* ### The Home page
***

![Homepage](assets/images/homepage.png)


  - The website design is one single home page, broken up into sections and navigated using internal links.
   The first section is "Our Services" giving the user bold and colourful images to lure users in. Clicking on the service generates a modal pop-up giving the user more information on that particular service. 
   The icon and text have been added so when hoovered over, the user can see what the image relates to. The image within the modal is different to the outer image. For example, the image of a young woman with a map leads to a vaccination modal with an image of a vaccine. This may put some people off if they have a needle phobia for example!
   
  - The second section is used to highlight the health advice the pharmacy can provide. This could be expanded to include advice on certain conditions, but would be too large to add in at this point. Instead, a link to the external NHS 111 website has been provided.
  
  - The third section is the contact form. Users can fill in this form to send the pharmacy a message. The enquiry section is a drop down menu to help the user direct the query to the correct channel.
  Once the user has completed the form and submitted, a thank you message appears. 

  - The Home page is fully responsive.
<br><br>

* ### Message Response Page
***
![response](assets/images/thankyou.png)


  - The message response page is a short, simple and bold design added in to the website. It is the second of two pages. I decided again including more on this page.
  - The navigation bar and burger menu was not included on this page, but replaced with a return to home page button at the end of the message, customised to be of similar style to the previous page.
  - This page is also responsive.
  
   <br><br>

* ### Website Footer
***
![footer](assets/images/footer.png)

 - The footer present on the home page holds links to its social media pages. Each link will open in a new tab to allow the user to easily switch between the two and not lose their original position on website. Footer uses Font Awesome icons.
 - The footer also contains a location map which the user can interact with, a fictional adress, and a message to contact a doctor is they have an urgent medical query.
 
 - The links are Facebook, Twitter and LinkedIn. Copyright information is also displayed.
<br><br>


* ### Future Features
***
  * An aesthetics section to include price list and how to arrange a consultation
  * As part of expanding the aesthetics side of the page, a responsive image gallery of previous cilents would be of benefit to the user.

<br><br>

## Design
***
   * ### Colour Scheme
      I wanted a colour scheme based around pharmacy and clinical colours - namely green, greys and white, to portray clean, crisp and bold styling. Fortunately the ideal green was already in the Bootstrap CSS from the Freelancer template. I did change the colours on the nav-bars, but reverted back to the default as the grey was a good unisex colour.
  * ### Favicon 
      I used the [Favicon.io](https://favicon.io/) website to create a favicon for my website. I wanted a mortar and pestle - a renowned image associated with pharmacy. I used the Font Awesome icon and styled it - using favicon to produce the file.
  * ### Typography
      I used the font within the template as I found this clean, fun and bold. I wanted a simple yet professional looking font, so avoided cursive or handwritting styles.
  * ### Imagery
      All imagery was sourced from pexels.com and had appropriate commercial licenses.

      I opted for images for links as opposed to an image gallery. Images were chosen that had bold colours and to act as click-bait.
  * ### Layout
      I eventually decided on a single flowing page. The bulk of the website information is presented on the homepage, which is neatly displayed using a bootstrap template which I have customised with my own CSS. 
      Initially I had designed a multiple paged website, but this kept on expanding beyond the scope of this project, so opted for a single scrolling page more suited to mobile users as the website is intending to target the younger user.

<br><br>

## Wireframes
***
Using Balsamiq I created wireframes for both a desktop browser and mobile phone browser. Please click links below:

- [Desktop Home Page Wireframe](assets/Wireframes/Homepage.pdf)
- [Desktop Image Gallery Wireframe](assets/Wireframes/Gallery.pdf)
- [Desktop Waiting List Wireframe](assets/Wireframes/Apply.pdf)
- [Mobile device Wireframe](assets/Wireframes/mobile.pdf)

<br>

## Technologies
***
* HTML
	* This project uses HTML as the main language used to complete the structure of the Website. The Gitpod template used was created by Code Institute
* CSS
	* This project uses custom written CSS to style the html.
* [Bootstrap](https://getbootstrap.com/)
	* The layout of the website was created from a Bootstrap template called Freelancer. The CDN is present in the head of the HTML code and the Javascript script required is present at the end of the HTML code.
* [Font Awesome](https://fontawesome.com/)
	* Font awesome icons are present throughout the website - the Navbar Brand (site logo) is prefixed with a font awesome icon. Each section includes a font awesome icon relevant to each piece of content. The footer present on each page also uses font awesome icons for each of the social media links. 
* [GitHub](https://github.com/)
	* GitHub was the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [Gitpod](https://git-scm.com/)
	* Git was used to create and edit all code used to build the website and store assets. It also functions as version control software to commit and push code to the GitHub repository where the source code is stored.
* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
	* Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles. Allows the testing of features/code without editing of your own HTML/CSS.
* [balsamiq Wireframes](https://balsamiq.com/wireframes/)
	* This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
* [MS PAINT](https://support.microsoft.com/en-us/windows/get-microsoft-paint-a6b9578c-ed1c-5b09-0699-4ed8115f9aa9)
    * Used to edit some of the images present on the website, mainly those used in the navigation bar.
* [Post CSS](https://postcss.org/)
    * I ran my code through this tool to ensure no errors were present and it was recommended to use to fix any errors with Ipad resolutions. 
* [Favicon](https://favicon.io/)
    * Favicon.io was used to make the site favicon - the font icon itself was taken from Font Awesome.
* [NVDA](https://www.nvaccess.org/)
    * NVDA screen reader software used to test the accessibility of the website
* [TinyJPGs](https://www.tinyjpg.com//)
* Used to compress image files to improve performance.
* Lighthouse
    * Lighthouse extenstion used to evaluate preformance.


<br>

## Test Strategy 
***

 ### Testing
  Testing for this website was done using the Microsoft Edge Browser and the built-in Chrome Developer Tools to check responsiveness on different screensizes and general debugging. Testing was also done on an iPhone 10 using Safari and Microsoft Edge. Testing was also carried out on a Microsoft Surface Pro 7 as I encountered some issues with landscape layout through the developer tools. No issues were found with responsiveness and previous issues have been dealt with through custom screen aspect media queries.
  
  In addition to my own testing, I sent my website link to family and friends and asked for them to test the website out using the same methods listed below.


The website contains no backend functionality therefore testing will concentrate on:

* Testing navigational links on each separate page, as well as the site logo which is designed to redirect to the home page
* Testing the responsiveness of the website, making sure the layout and navigational features remain user friendly with UX design maintained
* Testing of the form to ensure it functions correctly and does not allow an incomplete entry.
* Testing the form takes the user to the "thank you" page
* Testing out the "404" page if somehow the user manually keys in the website wrong or finds a broken link
* Testing the modals work correctly and display at all resolution breakpoints
* Testing the YouTube and Google map API links work correctly
* Testing the "growing list" link that should open up an external PDF file in a separate tab.
<br><br>

### User Stories Testing

***
   1. As a user visiting the site for the first time, I want to navigate the site quickly and efficiently.
   * Website visitor can navigate to the home page from any page in the website. This is either via the navigation menu, or the navbrand logo, as is standard on most websites.
   2. As a user, I want to know a brief history and story about the allotment site, any committee/manager involvement of the allotment site and other useful information.
   * Website visitor can browse the homepage which is broken up into sections. They are informed about the current allotment site, the committee team of the allotment, a site map of the allotment and other useful information about allotment ownership.
   * There is further information provided in modals on the homepage, detailing equipment needed, an on site shop and external information about growing produce.
   3. As a visitor, I want to view images of the allotment site and other related images such as vegetables grown on the site or the layout of other peoples allotments.
   * The website visitor can visit the image gallery page to view images of allotments, fruit/vegetables and other peoples allotments.
   4. As a visitor who is interested in owning an allotment, I wish to get on the waiting list for this allotment site.
   * The website visitor can apply to join the waiting list using the waiting list page. The page requires the user to fill in mandatory fields and presents the user with an acknowledgement once complete.
   5. As a user, I want to be able to contact the allotment site for further information without committing to the waiting list.
   * A user can contact the allotment site from a link on the homepage. They can also contact the allotment site from the thank you page once they have signed up for the waiting list.
   * A user can visit the allotment sites social media and contact the site via external means. These links are present in the footer bar on each page.
   6. As a website visitor, I want to know what items are available for sale in the on-site allotment shop. 
   * A visitor can click the allotment shop link on the home page and be presented with a current shop stock list and pricing.
   7. As a user, I want to be able to access your social media accounts.
   * A user can access the allotment site social media links via the footer in any of the pages that they find themselves on.
<br><br>
   ### Manual Testing
***
  * Navigation - Repeated steps on all pages.
      * Click on logo to confirm that it navigates to landing page.
       * Click on all navigation links to verify that they direct to the indicated page.
        * Verify that the current page the user is on, is highlighted as active in the menu.
        * Verify that the navigation menu is responsive to screen size and switches the navigational links to the "hamburger" icon on appropriately sized screens.
        * Ensure the hamburger menu opens correctly and displays the navigational links
        <br><br>
      * Home page
        * Verify that the google maps and youtube video load on all browsers and at all breakpoints. 
        * Verify that the images are correctly shown on all browsers and at all breakpoints.
        * Verify that the buttons present the user with the correct modals and external documents. Ensure that the modals display correctly on all screen sizes and can be closed easily by the user to return to the page behind.
        * Verify that all social media links displayed in the footer work correctly and open in a new page/browser tab
        <br><br>
      * Image gallery
        * Verify that all images load correctly
        * Verify that images are displayed within the gridbox layout on all screen sizes and are fully responsive.
        <br><br>
      * Waiting List
        * Verify that the form and image display correctly on larger screens
        * Verify that the image disappears on smaller screens and the user is only presented with the form.
        * Verify that the form works correctly - all required fields give a prompt if not correctly completed. Verify once form is completed and submitted that the user is taken to the acknowledgement page.
        <br><br>
      * Thank you page
        * Verify that page displays correctly, acknowledging the users form input.
        * Verify that the user can navigate back to the home page from the acknowledgement page.
        <br><br>
      * 404 page
        * Verify that the page displays correctly and that the user can navigate anywhere else on the site.
        <br><br>
      * Footer - Repeated steps on all pages.
        * Verify that the social media links open in a new tab.
        <br><br>

   ### Accessibility testing
***
  In order to test for accessibility, I used the windows program NVDA. NVDA is a screen reader software which reads out the webpage for visually impaired users. It also reads out clickable items on the webpage, any links, image descriptors, forms and buttons. Using this software I visited the live version of the website and allowed the screen reader to run through the whole website. There were no issues with the website in terms of accessibility. From running the software I noticed the footer bar links did not read out as they are only represented by a font awesome icon. I then added aria-labels in for each link to ensure accessibiilty is maintained throughout the website. The screen reader also highlighted the main buttons on the homepage (equipment list, growing list and allotment shop stock list) did not have appropriate labels - these were added accordingly.
<br><br>

  ### Feedback from User Testing
***
  The main piece of feedback from my user testing was in relation to the hamburger icon. Against UX design I have changed the icon to a plant rather than the traditional hamburger icon that people are familiar with. Some testers were not aware the plant represented a hamburger icon. To combat this, rather than changing the icon back to the traditional icon, I used the built in "beat" function that can be applied to font awesome icons. The icon now shows a "beating" animation which will draw the user to click the icon. Once the icon has been pressed, the icon stops beating, this was achieved using an "onclick" attribute on the icon which essentially removes the "fa-beat" from the span class once it has been opened. The beat will be re-applied if the user moves to another page or refreshes their current page, however the icon will have already achieved its intended purpose.
  <br><br>
        
### Validator Testing 
***
- HTML
  - No errors were returned when passing through the official [W3C validator]
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator]
<br><br>

### Unfixed Bugs
***
There are no unfixed bugs present within the website. 
<br><br>

### 404 Page Test
***
For the purposes of allowing the website reviewer to see the 404 page, the "email us" link on the home page purposely links to this. It would open up an email program to allow website users to email the allotment site otherwise.
<br><br>
## Deployment
***
Once the development process was well underway, the website was deployed to GitHub pages. In order to achieve this I: 

- Opened up the website repo in GitHub and opened the settings tab.
- The master branch was selected in the drop down menu to ensure my website was linked to correctly.
- Once this was selected the page is automatically deployed and the external website link is presented. 

The live link can be found here - https://graea85.github.io/Sprouton-Allotments/index.html
<br><br>
## Credits
***

* ### Code
<br>
The html and CSS code for the form was taken from https://colorlib.com/wp/template/colorlib-regform-3/. I then used my own custom CSS to redesign it to fit in with my website design and layout. I changed the image to a gardening themed image, added further form boxes to be relevant to my website and increased the radius of the borders. The image from the form is removed on smaller screen sizes for better UX design principles.
Bootstrap was used for all other code and styled using my own custom CSS. The home page layout is based on the bootstrap template at https://getbootstrap.com/docs/4.0/examples/carousel/ and styled with custom CSS.
I referred to W3Schools and Stack Overflow when I encountered issues, which were primarily to do with layout issues and media queries. I have put in several custom media queries to deal with display issues on the IPad mini and Ipad Air, specifically in portrait mode.
<br><br>

* ### Content
<br>
The images used in the project were all sourced from pexels.com or google images, ensuring they were available for commercial use.
The YouTube video on the homepage is property of The National Allotment Society.
The Google Maps API was created using google maps.

All information presented on the website was created by me unless specified. The external PDF file from the Growing List was produced by Wares of Knutsford, all copyright information is present on the PDF.

All icons used on the website were taken from [Font Awesome](https://fontawesome.com/)
