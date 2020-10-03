<h1 align="center"><a href="https://github.com/nualagr/eeefitness" style="text-decoration: none; color: #2D3142; font-weight: bold">EEE Fitness</a></h1>

<h2 align="center">Code Institute - Milestone Project 1</h2>

<img src="documentation/eeefitness-responsive-screenshot-different-screens.png" />
*Created at* [coolors.co](https://coolors.co/ffbe0b-fb5607-ff006e-8338ec-3a86ff).

EEE Fitness is a fictitious gym whose motto is Exercise Energize Empower. 
This project is the first of four Milestone Projects that make up the Full Stack Web Development Program at The Code Institute, and the main requirements were to make a static but responsive website with a minimum of 3 pages using HTML5 and CSS3.

Click <a href="https://nualagr.github.io/eeefitness/">here</a> view the website live.
<br />
## Table of Contents
1. [**User Experience (UX)**](#user-experience-(ux))
    - [**User Stories**](#user-stories)
        - [New User](#new-user)
        - [Returning User](#returning-user)
        - [Business Owner](#business-owner)
2. [**User Centered Design**](#user-centered-design)
    - [**1) The Strategy Plane**](#1-strategy-plane)
    - [**2) The Scope Plane**](#2-scope-plane)
    - [**3) The Structure Plane**](#3-structure-plane)
    - [**4) The Skeleton Plane**](#4-skeleton-plane)
        - [Wireframes](#wireframes)
        - [Features](#features)
    - [**5) The Surface Plane**](#5-surface-plane) 
        - [**Design**](#design)
        - [**Color Scheme**](#color-scheme)
        - [**Icons**](#icons)
        - [**Typography**](#typography)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Future Features**](#future-features)

3. [**Technologies Used**](#technologies-used)
    - [**Front-End Technologies**](#front-end-technologies)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Acknowledgments**](#acknowledgments)

<br/>

---
## User Experience (UX)
This section provides insight into the UX process, focusing on who the EEE Fitness website is for, the main aims of the project and 
how the website can help users meet their needs.

Project goals:
- To get users to sign up to become gym members
- To get users to enquire about becoming a gym member
- To facilitate those who wish to contact EEE Fitness
- To present users with information about the EEE Fitness gym so that they understand what facilities and services are available there, 
  where it is located, its opening hours, its membership packages and their respective prices.
- To create a website that is visually appealing, and fully responsive on all devices and screen sizes
- To make EEE Fitness seem a reputable business by creating a professional looking website

### User Stories

#### New User
I am a prospective gym member: 
- I need to be convinced why I should become a member of this gym. 
- I want to find out about the gym’s ethos.
- I want to find out where the gym is located.
- I want to find out the opening hours.
- I want to find out what gym facilities are available. 
- I want to find out what classes are on offer.
- I want to find out when those classes are run.
- I want to be able to read reviews of the gym written by gym members.
- I want to find out about the personal trainers and their qualifications.
- I want to find out what services are on offer at the gym.
- I want to find out how much membership to the gym will cost.


If I decide that I am interested in joining the gym: 
- I want to be able to contact the gym.
- I want to be able to sign up to become a gym member.

#### Returning User
I am a current gym member:
- I want to view the gym opening hours.
- I want to see what classes are on offer.
- I want to see what times the classes are running.
- I want to be able to book a place in a class.
- I want to be able to contact the gym and make an enquiry.
- I want to be able to leave a gym review.

I am a former gym member:
- I want to view the gym opening hours.
- I want to view the classes on offer.
- I want to see what times the classes are running.
- I want to be able to find out what services are on offer.
- I want to find out about the personal trainers and their qualifications.
- I want to find out how much membership to the gym now costs.
- I want to be able to contact the gym and make an enquiry about whether there is any discount for returning members.

#### Business Owner
I am the owner of EEE Fitness: 
- I want to encourage more people to sign up to the gym.
- I want to clearly display information about the gym in an attractive and informative way for both current and prospective members.
- I want visitors to the site to be able to contact the gym easily.
- I want prospective clients to be able to sign up easily.
- I want to encourage more visitors to follow the gym on social media and thereby raise the profile of the gym.
- I want to showcase positive reviews that the gym has received.
<br>
##### back to [top](#table-of-contents)
---
## User Centered Design
### 1 Strategy Plane
The User Centered Design process started with the creation of the User Stories.  These influenced subsequent feature, layout and design decisions.

The main business goal of the website is to attract new members to the gym or to encourage them to enquire about becoming members. 
The website follows the Business to Consumer model and is aimed at a fitness conscious audience. 
The site has been designed to provide minimal, but relevant, content that is easy to access, which satisfies the needs of both the business and its consumers. 
Imagery of fit individuals working out have been used extensively throughout the site in order to showcase the results the gym members can achieved.
Imagery of a wide variety of exercise equipment, the gym's facilities, has also been showcased.

### 2 Scope Plane
The key features of the website were developed based on the user needs. 

Users should be able to do the following on the website:
- Sign up to become a gym member
- Find out information about the gym’s: 
  * location
  * opening times
  * price plans
  * services
  * facilities
  * classes
  * class timetable 
- Learn about the benefits of becoming a member
  * membership packages
  * gym-member reviews
- Contact the gym with a question
- Visit the gym’s social media channels
- Learn more about the gym and its ethos

### 3 Structure Plane

After identifying the needs of the site's users and after visiting many gym websites the following website features were chosen

  *  opening times table
  *  gym address
  *  map showing the gym's location
  *  gym telephone number
  *  gym social media links
  *  contact us form
  *  sign up form
  *  hero images
  *  gym logo
  *  gym membership packages and pricing information section
  *  gym services information section
  *  gym facilites information section
  *  gym classes information section
  *  gym staff information section
  *  gym-member reviews

For ease of navigation it was decided to opt for a multi-page site, grouped into four pages: ‘Home’, ‘About, ‘Membership’ and ‘Contact’. 


### 4 Skeleton Plane

The UI wireframing tool, [Balsamiq](https://balsamiq.com/), was used to create wireframes for each site page as it would appear on desktop, tablet and mobile devices.

The main content areas were expressed in similar ways to create consistency across the site as a whole.  

A ‘hero image’, title and motivational heading was included at the top of each page.

In order to help users navigate through the site efficently a fixed navbar was decided upon for desktop viewers. 
The smaller, neater 'hamburger' icon with accompanying dropdown menu was chosen to provide mobile and tablet users with a less cluttered screen and therefore, a more pleasant browsing experience.
 
A footer, which contains the most sought after information: the site address, email address, telephone number, opening hours and social media links, was included at the bottom of every page.


#### Wireframes

##### Desktop
- [Home page for Desktop](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/desktop-home.png)

- [Facilities page for Desktop](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/desktop-facilities.png)

- [Classes page for Desktop](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/desktop-classes.png)

- [Membership page for Desktop](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/desktop-membership.png)

- [Contact Us page for Desktop](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/desktop-contact.png)

##### Tablet
- [Home page for Tablet](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/tablet-home.png)

- [Facilities page for Tablet](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/tablet-facilities.png)

- [Classes page for Tablet](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/tablet-classes.png)

- [Membership page for Tablet](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/tablet-membership.png)

- [Contact Us page for Tablet](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/tablet-contact.png)

##### Mobile
- [Home page for Mobile](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/mobile-home.png)

- [Facilities page for Mobile](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/mobile-facilities.png)

- [Classes page for Mobile](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/mobile-classes.png)

- [Membership page for Mobile](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/mobile-membership.png)

- [Contact Us page for Mobile](https://github.com/nualagr/eeefitness/blob/master/documentation/wireframe/mobile-contact.png)


### 5 Surface Plane

#### Design Choices
According to [statistica.com](https://www.statista.com/outlook/313/140/fitness/ireland#market-age) the highest percentage of gym-going users in Ireland in 2019 were in the 25 to 34 year-old age category. 
This cohort of society are mobile savvy and therefore a mobile-first approach was taken, helped by the use of the [Bootstrap Framework](https://getbootstrap.com/). 
These young professionals have disposable income it can be assumed they are looking for a professional gym that achieves results and provides them with a wide variety of workout options.
People in this age category are likely to be busy, working, commuting, socialising and to have family commitments, therefore time is a 
precious commodity to them. Because of this it is imperative that the site to be easy to navigate with key information intuitively located. 

#### Typography
According to [ilovewp.com](https://www.ilovewp.com/resources/wordpress-for-gyms/most-used-google-fonts-on-gym-websites/)’s article, 'Most Used Google Fonts on Gym Websites' *Open Sans* was the most popular font, 
therefore it was chosen as the main heading font.  [Google Fonts](https://fonts.google.com/) suggested *Roboto* as a complimentary font to *Open Sans*.  As this font was also the third most popular font choice
on gym websites, it was chosen as the main font for the body of the website.   

#### Icons
Icons were used alongside the text within the site in order to help the user to understand the content at a glance. 
They were taken from [Font Awesome](https://fontawesome.com/) and chosen to be self explanatory.

#### Colour Scheme
The colour scheme was chosen in order to convey a simple, clean and visually appealing site that evoked both an energetic, yet clean and professional atmosphere. Orange is colour that is traditionally associated with energy.  
White is a colour associated with cleanliness.  Grey is a colour associated with business and professionalism. 

<center><img src="documentation/eee-fitness-colour-palette.png" height="300" width="600" alt="EEE Fitness colour palette" /></center>

*Colour palette created at* [coolors.co](https://coolors.co/ffbe0b-fb5607-ff006e-8338ec-3a86ff).

- #2D3142, Space Cadet, which a relatively dark, professional looking grey, was chosen for the navigation bar and the footer. 
As most gym equipment is grey in colour, shades of grey appeared to be appropriate for the functional navigational bar and the footer.
- The background colour of site is #FAFAFA, Cultured, a subtle white colour, to keep the website’s image clean and to provide easy contrast.
- Active links are be displayed in #FC7536, Orange Crayola.  Non-active links change from Cultured Orange Crayola when hovered over in orer to provide visual feedback to the user. 
To be consistent the social media links in the footer behave in a similar fashion.
- #FC7536, Orange Crayola, is used as an accent colour throughout the site, from the logo to providing a striking contrasting background colour, to call-to-action buttons.  Where a stronger contrast was desired #FB5607, Orange Pantone was used in its stead.
- #D3D3D3, Light Grey, was used instead of Cultured in areas where it was deemed that it would produce a softer contrast, for example it was 
used as a muted text colour in the footer and as a background colour for the inactive class timetable tabs. 
- Text colour throughout the site is Cultured, Light Grey or Space Cadet, depending on which proved easier for the user to read against the assigned background colour of the element in question.

##### back to [top](#table-of-contents)
---

## Development
In Mentor Session 1, Mr. Reuben Ferrante suggested that a more efficient layout for the About page was necessary as the wireframe layout chosen would result in an unpleasant user experience for the mobile user.  
Both tab and dashboard layouts were considered before the final layout of separate pages for Services, Facilities and Classes was chosen.  
The About page information relating to the gym staff and services were included on the Home page and the site structure create six main pages: Home, Facilities, Classes, Membership, Contact and Sign Up.  This structure should allow the end user to access the information that they seek with fewer clicks, hopefully leading the user toward continuing the browsing experience.
<img src="documentation/eeefitness-site-map.jpg" height="auto" width="100%" alt="EEE Fitness site map" />
*Site Map was created using* [Microsoft Word](https://www.microsoft.com/en-ie/microsoft-365/p/word/cfq7ttc0k7c7?=&ef_id=Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB%3aG%3as&OCID=AID2100139_SEM_Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB%3aG%3as&lnkd=Google_O365SMB_App&gclid=Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB&activetab=pivot%3aoverviewtab).


My mentor also helpfully showed me how to embed a Google Map in order to allow visitors to the site to locate the gym more easily.  Initially this was included soley in the Footer section of the desktop view, however when it came to building the site it was also added to the footer when viewed on a tablet.  This decision was taken partly for aesthetic reasons and partly because it was pointed out to me that many tablet users use their device as a replacement for a desktop computer and therefore expect much of the functionality of the desktop view when browsing online.

## Features

The project consists of different pages, all of which can be accessed through the menu in the navigation bar.

#### Consistent features across all pages:
- The fixed navigation bar containing the menu at the top of the page is consistent across all pages, however it has been condensed into a drop-down menu on tablet and mobile devices in order to streamline the appearance.
- The footer containing contact details and social media icons is consistent across all pages.

#### Features to be implemented in the future:
- An online booking system for classes that current gym members can access through the website.
- A payment system so that people can buy their membership package immediately from the site.
- A link to TrustPilot or a similar consumer review website where the gym’s current members can share their positive experiences at EEE Fitness.

## Technologies Used:
- Languages: 

  * [HTML5](http://en.wikipedia.org/wiki/HTML5)
  * [CSS](http://en.wikipedia.org/wiki/CSS)
  * [JavaScript](https://en.wikipedia.org/wiki/JavaScript). JavaScript was imported from Bootstrap for the responsive navbar, the testimonial carousel and the tabbed navigation pane on the classes.html page.

- Websites
  * [Gitpod](https://www.gitpod.io/). Online IDE used to build and develop the website.
  * [Coolors](https://coolors.co/ffbe0b-fb5607-ff006e-8338ec-3a86ff). Used to choose a colour scheme.
  * [Bootstrap Framework](https://getbootstrap.com/). Used to structure the website layout and ensure that it was responsive on all devices.
  * [Github](https://github.com/). Used to host the deployed site and used as a respository for all previous versions of the build.
  * [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools). Used extensively throughout the project to test the responsiveness of elements, to target and apply CSS styles during the design phase and to test the site's performance once built. 
  * [Google Fonts](https://fonts.google.com/). Used to choose and source the fonts used on the site.
  * [Font Awesome](https://fontawesome.com/). Used to source the free icons used in the Services section, used as the social media links in the footer and used for the favicon.
  * [Pexels](www.pexels.com). Used to source royalty free images.
  * [Unsplash](www.unsplash.com). Used to source royalty free images.
  * [Burst](https://burst.shopify.com). Used to source royalty free images.
  * [Pixabay](www.pixabay.com). Used to source royalty free images.
  * [Optimizilla](https://imagecompressor.com/). Used during the testing phase in order to compress the photographs to reduce the site loading time.
  * [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator). Used to validate the CSS file.
  * [W3C HTML Validation Service](https://validator.w3.org/#validate_by_uri). Used to validate the HTML files.
  * [Code Institute](https://codeinstitute.net/). Used to review concepts covered in preceding modules and walk-through projects. 
  * [Slack](code-institute-room.slack.com). Used during all phases of development and testing to find the answers to questions and the solutions to problems enountered.
  * [Stack Overflow](https://stackoverflow.com/). Used to search for the answers to problems encountered during the development and testing of the website.
  * [Am I Responsive](http://ami.responsivedesign.is/).  Used to create the mock-up image at the top of this document which shows the site as it would behave when viewed on desktop, mobile and tablet devices. 
- Apps:
  * [Balsamiq](https://balsamiq.com/). Used to create the project wireframes.
  * [Inkscape](https://inkscape.org/). Used to edit FontAwesome icons that were used as bullet images and as the Favicon.
  * [Microsoft Word](https://www.microsoft.com/en-ie/microsoft-365/p/word/cfq7ttc0k7c7?=&ef_id=Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB%3aG%3as&OCID=AID2100139_SEM_Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB%3aG%3as&lnkd=Google_O365SMB_App&gclid=Cj0KCQjwwuD7BRDBARIsAK_5YhXETvfhSIhKaGdssIQw29SJmGZ4uWT6YF9Tfd1-1qMY2mSRD4t5F2oaAo-iEALw_wcB&activetab=pivot%3aoverviewtab). Used to create the hierarchical representation of the site layout.

  
## Testing.
[Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) were used extensively throughout the development process in order to test whether elements were responsive when viewed on mobile and tablet devices. When problems were encountered the Device Selector was used to target the element.  Using the Elements Panel in Developer Tools the code in question was altered in order to achieve the desired result. 
Working code snippets were then replicated in the style.css file in Gitpod. Other solutions for errors were found in the Code Institute Slack channels, on Stac.  

[W3C HTML Validation Service](https://validator.w3.org/#validate_by_uri) was used to validate the code. It highlighted some errors across the site which have since been recitified: 
- button tags were used incorrectly within anchor tags
- paragraph tags and text that would have displayed if the browser did not support iframes appeared as an error in the HTML validator and were therefore removed
- the frameborder attribute on the iframe element was removed as it is now obsolete.
- errant spaces in the tel attribute of the anchor tags in the footer were deleted.
- a break element was moved from being a child of the unordered list tag in the footer and placed inside the list element.
- another errant break tag, also a descendant of the unordered list in the footer, was removed entirely and a bottom margin was added to the container in its place.
- the section tags were removed from around the jumbotron on each page as they did not directly contain a heading tag and were showing up as a warning in the HTML validator.

The site currently has no errors:
<img src="documentation/html-validator-no-errors-page.png" height="auto" width="100%" />


[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator) was used to validate the style.css file.  It highlighted some errors which were then resolved:
- the scrollbar-width property was removed from the .hide-scrollbar class as it no longer exists as a property.
- a missing curly brace was inserted in the CSS file.
- a forward-slash character, left over from a deleted comment, was causing a parse error in the CSS file and was removed.

The style.css file currently has no errors:
<img src="documentation/css-validator-no-errors-page.png" height="auto" width="100%" />

The website was then tested using the Google Chrome Developer Tools Lighthouse test. 
Initially the site received a 72% rating on performance, largely due to the size of the images.
<img src="documentation/lighthouse-first-results-mobile.png" height="auto" width="100%" />

The images were then compressed using Optimizilla and uploaded to the site.  
The subsequent test results were not satisfactory.  Smaller versions of the images were then downloaded from their respective sites and these images were compressed before being uploaded to Gitpod. The third test resulted in a marked improvement in performance when tested in Lighthouse.
<img src="documentation/lighthouse-third-results-mobile.png" height="auto" width="100%" />

<img src="documentation/lighthouse-third-results-mobile-performance-breakdown.png" height="auto" width="100%" />


The site performed well in the Lighthouse test for desktop viewing:
<img src="documentation/lighthouse-third-results-desktop.png" height="auto" width="100%" />
<img src="documentation/lighthouse-third-results-desktop-performance-breakdown.png" height="auto" width="100%" />

### Browsers Tested
The website has been tested in the following browsers:
- Chrome Version 85.0.4183.121 
- Samsung Internet Version 12.0.1.47	
- Microsoft Edge Version 85.0.564.63 
- Opera 70
- Mozilla Firefox 81.0.1
The website works and functions as expected on Samsung Internet, Google Chrome, Microsoft Edge and Opera.  When opened in Firefox, however the custom svg bullet points do not always render.  
This is a known issue. I have decided to leave it for now and detail it in the README as the only current error I have come across on the project.

### Bugs
The custom svg bullet point images do no render in Mozilla Firefox 81.0.1 (64-bit). 

## Deployment


## Acknowledgements
- 
- [statistica.com](https://www.statista.com/outlook/313/140/fitness/ireland#market-age)’s digital marketing outlook article on the Fitness Sector in Ireland.
- [offsprout.com](https://offsprout.com/blog/10-best-website-designs-for-gyms-2019/)’s article on The 10 Best Website Designs for Gyms and Fitness (2019 edition). 
- [ilovewp.com](https://www.ilovewp.com/resources/wordpress-for-gyms/most-used-google-fonts-on-gym-websites/)’s article, “Most Used Google Fonts on Gym Websites”. 
- [Code Institue](https://codeinstitute.net/5-day-coding-challenge/?utm_term=code%20institute&utm_campaign=a%26c_BR_IRL_Code_Institute&utm_source=adwords&utm_medium=ppc&hsa_net=adwords&hsa_tgt=kwd-319867646331&hsa_ad=417883007028&hsa_acc=8983321581&hsa_grp=56427889338&hsa_mt=e&hsa_cam=1378516521&hsa_kw=code%20institute&hsa_ver=3&hsa_src=g&gclid=CjwKCAjw74b7BRA_EiwAF8yHFIDc09EJev6sA8NIXe-u-TOM6nIkNPI8co9lLsTOpib4Oe8QaJ7k6xoCgNQQAvD_BwE&gclsrc=aw.ds) and the very helpful tutors.
- My mentor for this project Reuben Ferrante for his help and guidance. 

## Images Used:


### index.html
- hero image   
https://www.pexels.com/photo/woman-kneeling-with-barbel-on-shoulders-3076514/
Photo by Jonathan Borba from Pexels
- gym member male image to accompany testimonial  
https://www.pexels.com/photo/man-wearing-black-crew-neck-shirt-and-straight-cut-jeans-804009/
Photo by Samad Ismayilov from Pexels
- gym member female - Janet Doe - to accompany testimonial  
https://www.pexels.com/photo/adult-blond-confidence-confident-1146352/
Photo by mentatdgt from Pexels
- gym member female - Jane Doe - to accompany testimonial  
https://www.pexels.com/photo/selective-focus-photo-of-smiling-woman-in-active-wear-carrying-gym-bag-3764401/
Photo by Andrea Piacquadio from Pexels
- male trainer 1 image  
https://www.pexels.com/photo/man-in-black-crew-neck-t-shirt-standing-in-front-of-boxing-gloves-3912953/
Photo by ThisIsEngineering from Pexels
- trainer female  
https://unsplash.com/photos/HzXDD6l7gW4
Photo by ŞULE MAKAROĞLU on Unsplash
- male trainer 2 image  
https://www.pexels.com/photo/man-in-black-tank-top-holding-orange-towel-3917685/
Photo by Andrea Piacquadio from Pexels

### facilities.html
- banner image  
https://www.pexels.com/photo/brown-wooden-chess-piece-on-black-computer-keyboard-4753885/
Photo by cottonbro from Pexels
- cardio zone image  
https://www.pexels.com/photo/an-on-treadmill-1954524/
Photo by William Choquette from Pexels
- free weights image  
https://unsplash.com/photos/CQfNt66ttZM
Photo by Danielle Cerullo on Unsplash
- strength training image  
https://www.pexels.com/photo/serious-sportsman-training-on-exercise-machine-in-modern-gym-3838937/
Photo by Andrea Piacquadio from Pexels
- functional training zone image  
https://www.pexels.com/photo/adult-athlete-body-bodybuilding-414029/
Image by Pixabay

### classes.html
- banner image   
https://www.pexels.com/photo/group-of-women-doing-exercise-3768695/
Photo by Andrea Piacquadio from Pexels
- pilates image  
https://www.pexels.com/photo/group-of-woman-doing-yoga-868483/
Photo by Andrea Piacquadio from Pexels
- kettlebells image  
https://www.pexels.com/photo/athlete-barbell-bodybuilder-bodybuilding-416717/
Image by Pixabay
- spinning image  
https://pixabay.com/photos/sports-indoor-cycling-fitness-gym-1962574/
Image by Александр Вальков from Pixabay
- zumba image  
https://unsplash.com/photos/3ckWUnaCxzc
Photo by Danielle Cerullo on Unsplash
- yoga class image  
https://www.pexels.com/photo/women-keeping-fit-3984353/
Photo by Gustavo Fring from Pexels
- boxercise  
https://burst.shopify.com/photos/kick-boxing-fitness?q=kickboxing
Photo by: Nicole De Khors on Burst

### membership.html 
- banner image  
https://www.pexels.com/photo/people-holding-a-weights-3766211/
Photo by Andrea Piacquadio from Pexels

### contact.html
- banner image  
https://www.pexels.com/photo/man-holding-brown-rope-3253501/
Photo by Cesar Galeão from Pexels

### register.html
- banner image  
https://www.pexels.com/photo/photo-of-person-using-treadmill-3757957/
Photo by Andrea Piacquadio from Pexels
