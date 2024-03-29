# Table of Contents #
- - - -
# Project Goals #
## 1. User goals
- The users goal is to gather information about popular rural travel destinations in Wales

- The users goal is to being able to navigate the website quickly and efficently to our content

- The users goal is to use our information presented to make their travel decisions 

- The users goal is to find their rural destination and research more about events, food, local history and location
    
## 2. Site Owner Goals
- The site owner goal is to provide unbiased comprehensive rural travel-related content

- The site owner goal is to increase rural tourism to Wales

- The site owner goal is to take feedback from users and provide better travel experiences & information to the public
- - - -
# Features #

## Index Page
### Carousel
The site features a way to display information on how to best tour Wales, it’s home page prominently features a carousel of hero images that can display the best that Wales has to offer. 
### Cards
Below that are 3 cards that feature guides available with a short snippet of information and you can quickly choose the guide you wish rather than browsing the entire guide page. Selecting the guide you want will send you to the correct section of the guides page via an ID.  The cards are responsive going into a single column on a small screen and showing as a row of 3 on medium and larger screens.
Below that is some information regarding Welsh rules on wild camping.

## Guides Page
The guides page is multiple pages in one and can be expanded downwards with further guides. It is responsive showing as a single column on smaller screens and two on medium and larger screens. The order on smaller screens is image > text > image > text however on medium and larger screens it will alternate to make the site more visually interesting and balanced. The guides have an accordion element from bootstrap that can be used to store extra information, a map iframe has been used as an example.

## Contact page
This page has used the min() function to fluidly size for many screen sizes at and between breakpoints to ensure a consistent view, the body is size to the viewport to ensure the footer remains at the bottom of the page without using a fixed position as fixed position cause issues with overlapping of the form and footer at smaller screen sizes

- - - -
# UX/UI #

   ## 1. Target Audience
   
  - People looking to travel rurally
  - People specifically looking for Wales based rural trips
  - Users looking for rural travel tips in Wales
  - Users already in the destinations looking for events or points of interest
  - The Welsh travelling community 

 ## 2. User Stories
  - As a first time user, I want a navbar to easily navigate to the content I want.
  - As a first time user, I want an introduction, blurb or image to easily understand the main purpose of the site.
  - As a first time user, I want a guide/article to get a general rundown on the location. (i.e Transport, accommodation, events, food/drink, local history)
  - As a  first time user, I need a map of the location.

  - As a returning user, I want to contact the organisation to provide feedback
  - As a returning user, I want to leave a review

  - As a site owner I want a logo in order to help identify the brand.
  - As a site owner, I want users to find the visually pleasing travel content easily.
  - As a site owner, I want users to be able to book or find out more on the respective websites mentioned in the content
  - As a site owner, I want to display an engaging carousel of hero images so that users are more likely to book tours
- - - -
 ## 2. Design Choice
 
 ##  Colour Scheme

 - A earthy/rural palette was picked by the team in fitting with the outdoors nature and rural travelling to align with our target audience 
 - Inspired by https://coolors.co/cc3f0c-72705b-0f1a20-a1cca5-fffdf7
 
 ##  Fonts
 
 ### Main Content 
 - Didact Gothic
 ### Home Title & Wild Camping  
 - Wales Sans Headline
 
 ## Wireframes
    
  - Main Page Wireframe
  <div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/2dba9214-6f88-4ed3-97f6-741d84b9ec33" alt="Main page wireframe">
</div>

  - Article Page Wireframe

  <div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9896a627-c591-4829-b0ab-add8ffb007bf" alt="Wireframe">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/9f047ef6-5fb3-4394-8fae-22f964d49008" alt="Wireframe">
  </div>
  

  - Contact Page Wireframe
<div align="center">
  <img src="https://github.com/Karlsberg62/Hackathon1/assets/149387764/ba3ef148-a6e7-43c1-af73-962268604127" alt="Wireframe">
</div>

 ## Logo

- Created by Graeme (Gray) Adamson Logo 1 Logo 2. Used a CSS file and HTML file to create it
- CSS file is in the assets folder in the CSS sub-folder which were used to generate logo files are logo.css and logo.css
- Images used are in the assests folder in the logo sub-folder files are Web%20capture_10-1-2024_165527__resized.jpeg (logo) and Web%20capture_10-1-2024_173633__resized.jpeg (logo2)
- Team decided on logo2
- - - -
# Testing #

## HTML Validation
- Initial HTML Validation was performed using the W3C Mark up service and the results can be found in this document. https://docs.google.com/document/d/1bpeozgiIdqKK1ukf-Le-pkrP0iTv6WHeWEdsZ5wpVN4/edit?usp=sharing
- The missing P element & the duplicate attribute on class in the Guide.html has been resolved.
- Any issues with the index.html & contact.html page have remained as future fixes.
  
## CSS Validation
- Initial W3C CSS style sheet validation link https://docs.google.com/document/d/1PLn-LXFHKpIaeiYMOUwEe_7h6ZVjw1cCxucjCS2Kp-w/edit?usp=sharing
- Test W3C Validation CSS style sheet validation https://docs.google.com/document/d/1t1xgVG540joh549TvAwI0CXQ889QDUD3y8Qt0xqJFtU/edit?usp=sharing
- The style.css form passed with only one issue that was with a newer feature that some browsers do not support just yet. We have left this in as the browsers still work as intended.

## Accessibility
- We entered our website through AccessScan to check we were compliant with with ADA standards. Our website is ADA-compliant as shown below:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/da66d426-6223-48f4-afc3-1a122a9ad6c0)

## Device Testing

We have tested the site with the following devices:

- Android Google Pixel 5
- Desktop
- Android Tablet
- Chrome Developer Tools (Simulating for all available device options)

The site functioned as expected except for the loading on the guide page with the map & Youth Hostel content on smaller devices.
  
## Browser Testing

Testing has been done on the following browsers:

- Chrome (& Developer tools)
- Opera
- Safari

## Testing Breakdown
- We completed the following tests on all mentioned devices and browsers including the steps & outcomes from said tests. Any noted bugs are explained below.
  
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/bb6a250c-5003-462c-a133-506bd18537bf)

## Testing user stories

We tested our site vs the user stories: 

1. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e52c926b-713d-4ba0-823e-1f58e58e711b)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e0ad468c-ac68-40ef-a7ef-3a08fbedf058)
--
2. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/2561b52a-af2b-4239-a386-f87a8ab0c498)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/b590ea37-34a5-4404-a1ed-fb8745a28e9e)
--
3.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/649049fb-25a6-4035-8e80-49bb07d24543)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/30c82c1e-28ea-4403-8b10-3371da297aff)
--
4.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/14cdc8b8-7450-46d2-bde5-673bbe6a3ecc)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e9ecbba4-dd1c-43a4-b6a1-be45d7c765cd)
--
5. 
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/79e8300a-3523-485e-8304-147c1d4a3e81)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e0ad468c-ac68-40ef-a7ef-3a08fbedf058)
--
6.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/3e4f9313-b077-40a9-bd7f-c287907d2e2d)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/89967414-9cbc-4e35-a16c-7bcc879abb2e)
--
7.
- This user story combines the Must Have User Stories for Outsourcing content, YHA Booking Link & Hyperlinking Content
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/0f8cf269-4724-478c-b033-4228330d7cc1)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/8977ba5d-0f7b-4c43-9946-1ae94c78ff7e)
--
8.
User Story:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/e7e29e5f-ee27-4c50-bd9c-176bc30fd820)
Site Example:
![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/0b6c59b5-dc37-4144-b349-e00e06ab50e0)

## Known Bugs

## During development, we found these bugs and fixed them:

### Nav bar disapperance

- On smaller devices, the navbar burger logo to indicate the nav bar would disappear when switching to the guide page.
- To fix this issue, we chekced the Home & Contact nav bar, realised they had no issues and copied the code back into the guide HTML.

### Carousel Images poor quality on smaller devices

- The carousel originally loaded on all devices, however the images appeared pixelated & poorly rendered.
- To fix this issue, as a design choice, we decided to remove the carousel feature to mobile users to keep a high quality of user experience.

## During development and testing, these are the current bugs:

### Guide Page Map on smaller devices

- The map, once toggled, spills over into excess space. While the user can still use the map and function, this is not a good user experience & would be reviewed in our next sprint if we had time

### Youth Hostel Content on smaller devices

- The content when deployed on a smaller device reshuffles the image to the bottom of the container.
- The text in the last paragraph changes to the default font rather than our applied styling in the CSS folder. This is specific to Android.

![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/ca3315f9-de44-4588-8d92-ac96145639fc)
- - - -
# Deployment #

How this site was deployed

- In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu 
- From the source section drop-down menu, select the Main Branch
- Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment
- Any changes pushed to the main branch will take effect on the live project

- The live link is here: https://karlsberg62.github.io/Hackathon1/

- We used an agile methodology by using early deployment. We could see every change on a live site to aid our development process
- ![image](https://github.com/Karlsberg62/Hackathon1/assets/149387764/cad5ad9d-e0df-491f-982b-198d6f917797)

- - - -
# Sources #

## Media
 - The following photos were used in the carosel: [Carosel Image Sources.docx](https://github.com/Karlsberg62/Hackathon1/files/13889520/Carosel.Image.Sources.docx)
 - The following photos were used in the content: [Content Section sources.docx](https://github.com/Karlsberg62/Hackathon1/files/13889524/Content.Section.sources.docx)
 - The logo photo was edited with: https://www.online-image-editor.com

## HomePage Content. 
-  This site was used as the key reference for the home page content. https://wanderingourworld.com/wild-camping-in-wales/
-  The Text for the Home Page Content can be found here - https://docs.google.com/document/d/1Bl_0SjuOEjraYlO66AGGKhX8v8vlVn-y2hpFr8K7KuM/edit?usp=sharing

## Content
- The colour scheme was helped with the use of: https://coolors.co
- The fonts were imported from Google Fonts.
- The Wales Sans Headline font was imported specifically from: https://www.onlinewebfonts.com/download/87c492db36d96bca8d9d769a21874b83
- Font awesome was used to add icons for UX purposes.
- Balsamiq was used to create the wireframes during the design process.
- The background texture is from: https://www.transparenttextures.com/

## Code
- The Logo CSS code orginated from here: https://www.w3schools.com/howto/howto_css_shapes.asp
- The HTML & CSS uses Bootstrap Version 5.3: https://getbootstrap.com/docs/5.3/getting-started/introduction/

# Future Features #
- The development team would like to add a toggle button on the navigation bar that allows the site to be viewed in Welsh. This would be an additional UX design feature to promote to welsh users.
- The development team would like to implement a review system where users can leave reviews & feedback that would be shown on the site. This requires an API/database that is not currently within our scope.
- - - -
