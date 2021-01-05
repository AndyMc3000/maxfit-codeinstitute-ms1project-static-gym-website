<a name="top-of-page">![M A X F I T Logo created using FreeLogoDesign.org](/assets/readme-assets/maxfit-logo-readme.png)</a>

# MaxFit.com - Gym & Fitness Club :weight_lifting: #
## Code Institute - Dip. in Software Development - Milestone Project 1 - User Centric Front-End Development ##
#### Student: Andrew McDonald - Contact me on GitHub :octocat: - <a href="https://github.com/AndyMc3000"><strong>AndyMc3000</strong></a> ####

<hr>
<img src="assets/readme-assets/maxfit-ami-responsive-homepage.png" width="630">
<hr>

## Table of Contents ##
1. [Introduction](#introduction-heading)
1. [User Experience Design (UX)](#user-experience-design)
1. [Development Process](#development-process)
1. [Website Features](#website-features)
1. [Technologies Used](#technologies-used)
1. [Testing & Bugs](#testing)
1. [Deployment](#deployment)
1. [Credits](#deployment)
<br>
<hr>

## 1. <a name="introduction-heading">Introduction</a> ##

The MaxFit website is my Milestone Project 1 (MS1) for my Diploma in Software Engineering course at Code Institute. The below refers to MaxFit as a fictional client of mine, where I have been hired to develop a website for them to meet certain requirements (see UX section below). However the underlying goal of the project is to meet and exceed the requirements laid out for the MS1 by Code Institute. The main goal of the MS1 is to "..build a static front-end site to present useful information to users, using all the technologies that you have learned about so far." Those principle technologies being HTML5, CSS3, and Bootstrap front-end framework.

MaxFit is a Gym and Fitness Club based on the beautiful shores of Lough Leane, Killarney. MaxFit is run by a passionate and inclusive group of fitness experts and professionals, and boasts state-of-the-art equipment and facilities. At MaxFit, their goal is to maximise the potential within their members.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 2. <a name="user-experience-design">User Experience Design (UX)</a> ##

The design of this website was determined by assessing and quantifying the goals and objectives of the website owners, as well as the requirements of end users who will visit and use the website. Following the determination of 'Client' and 'User' stories and their subsequent technical requirments, the site was designed using the principles of Jesse James Garrett's '5 Planes of UX Design'. The outcome or tasks created for each plane is outlinined below.

### The 5 Planes of UX Design: ###

#### 1. The Strategy Plane ####

The Strategy Plane is, as defined by Jesse James Garrett "..incorporates not only what the people running the site want to get out of it but what the users want to get out of the site as well." 

Please see below details of 'Client Stories' to detail the requirements of the MAXFIT business owners, and 'User Stories' which highlight the requiremnts of end users of the MAXFIT website.

#### Client Stories ####
> - [x] “The main goal of the website is to attract new customers, and provide value to existing customers in the information is provides.”
> - [x] “The website must show and promote the quality of the facilities at MAXFIT.”
> - [x] “The website must detail Membership costs and features (Gold & Silver Passes, each with 3-month, 6-month, 12-month, student/senior pricing).” 
> - [x] “The website must allow people to easily contact MAXFIT to arrange a free fitness consultation.”
> - [x] “The website must promote details about MAXFIT’s 1-month free trial membership offer.”
> - [x] “The website must promote MAXFIT’s Personal Training services.”
> - [x] “The website must detail the classes MAXFIT currently offer and highlight their costs and schedule/frequency.”
> - [x] “The website must visually appeal to potential customers from all walks of life. MAXFIT is not just a ‘hard-core workout’ gym, it is an fitness and wellness centre too. MAXFIT’s range of services appeal to customers of all age groups, male and female.”
> - [x] “The website must promote the fact that MAXFIT offers 24-hour access.”
> - [x] “The website must promote MAXFIT’s social media channels” 
> - [x] “The website must show some testimonial quotes”
> - [x] “There must be a system in place to track website usage statistics and end user interactions. All MAXFIT owned internet-connected computers, routers, or devices should be automatically excluded from website statistics/reports.”
> - [x] “The website must be mobile-friendly.”

#### User Stories ####
> - [x] “I want to see what kind of facilities MAXFIT have.”
> - [x] “I want to find about the different classes MAXFIT run.”
> - [x] “I want to find out when certain classes are on at.”
> - [x] “I want to be able to see where MAXFIT is located.”
> - [x] “I am interested in a membership and want talk to someone about what is best for me.”
> - [x] “I am interested in a membership and want to understand what the costs are.”
> - [x] “I want to find out a little bit about the people who work at MAXFIT.”
> - [x] “I want to see what other people say about MAXFIT”.
> - [x] “I want to find the MAXFIT social media channels.”

#### 2. The Scope Plane ####

Based on the outcomes the Strategy Plane, The Scope Plane determines what features, functionality, and types of content, should be included within the scope of the project. Listed below are the functional specifications and content requirements decided upon for the MAXFIT website. 

#### Functional Specifications: ####
* Build a esponsive Website with 6 pages - Home, Services, Classes, Membership, Team, Contact.
* Use photo/image carousel at top of homepage.
* Homepage carousel to include link to free consultation contact form.
* Contact form required for free trial sign-up form.
* Contact form required for membership sign-up.
* A main photo Gallery using a pop-out modal carousel, and similar galleries for indivudual services and classes.
* Use a bootstrap Jumbotron for the top of all other pages to promote contact.
* Google Analytics integration.

#### Content Requirements: ####
* Inspirational images & messaging throughout.
* Photos of the facilities, equipment, and members using services.
* Testimonial sections.
* Pricing table.
* Promotional sections for Free Trial and Free Consultation.
* Personal Trainer motto’s.
* A main Image gallery for homepage and other locations, and individual galleries for services and classes.

#### 3. The Structure Plane ####

#### Interaction Design: ####

Interaction design is defined as the "..development of application flows to facilitate user tasks, defining how the user interacts with site functionality" Inline with this principle, the pages were designed as follows;

1. The Homepage;
* It should have a navigation bar with individual links to each page.
* It should contain a call-to-action to promote the free fitness consultation offer. This should link to a contact form on the contact page.
* It should contain a section to promote free trial offer. This should link to a contact form on the contact page.
* It should also contain a ‘why us’ section highlighting 4 main features/benefits of using MAXFIT - The Gym/equipment, Personal Training, Classes, and Membership benfits. The would link to relevant pages via buttons.
* It should contain a section to show Testimonial quotes.
* It should have a furthe navigation section in the footer. The footer will also contain links to all MAXFIT's social media channels.

2. The Services page;
* It should have the same navigation bar and footer as described un The Homepage section above.
* It should have 3 main sections focusing on; The Gym/equipment, Personal Training Services, and the Studio/class facilities.
* The sections should show detailed text information and a gallery of photographs.

3. The Classes page;
* It should have the same navigation bar and footer as described un The Homepage section above.
* It should contain a short section giving details of what each class is, a link how much it costs, what the current timetable for the class is, and who runs the class.
* Each section should also contain images/gallery relevant to the class.

4. The Membership page;
* It should have the same navigation bar and footer as described un The Homepage section above.
* It should contain pricing information for the different offerings/packages.
* It should contain a 'hero' section which details the Free Trial offer. This should link to the Free Trial sign-up form.

5. The Team page;
* It should have the same navigation bar and footer as described un The Homepage section above.
* It should contain contain information about the site management team and personal trainers.
* It shoud offer a quoick bio, a photo, and qualification details for each team member.
* It should contain messaging around a mission statement.

6. The Contact page;
* It should have the same navigation bar and footer as described un The Homepage section above.
* It should contain address and contact information.
* It should include a Google Map.
* It should contain a contact form with a dropdown to allow users to indicate their are of interest: Sign-up to a plan, Free Trial, or Free Consultation.

#### Information Architecture: ####

Infromation Architechture is defined as; "The structural design of the information space to facilitate intuitive access to content" (Copyright 2000 James Garrett). As such MaxFit was designed to allows a user to find the information they need easily. For example, the navigation bar is fixed to the top of the page view so is always immediately accessible, and buttons and links are clearly visible and communicate their purpose in an unambiguous way.

The structure of the website and outline of page sections is outlined in the Sitemap. Click the link to view the <a href="assets/readme-assets/maxfit-sitemap-final.png"><strong>Sitemap.</strong></a>


#### 4. The Skeleton Plane ####

Based on the structure decided upon, The Skeleton Plane ".. The skeleton is designed to optimize the arrangement of these elements (such as the placement of buttons, tabs, photos's and blockd of text) for maximum effect and efficiency..".

With this in min the following wireframes were created to detail the layput of the website pages and individual sections/containers. Please click the following links to view these wireframes.

1. <a href="assets/readme-assets/maxfit-homepage-wireframe.png"><strong>Homepage Wireframe</strong></a>
1. <a href="assets/readme-assets/maxfit-services-page-wireframe.png"><strong>Services page Wireframe</strong></a>
1. <a href="assets/readme-assets/maxfit-classes-page-wireframes.png"><strong>Classes Wireframe</strong></a>
1. <a href="assets/readme-assets/maxfit-membership-page-wireframes.png"><strong>Membership Wireframe</strong></a>
1. <a href="assets/readme-assets/maxfit-team-page-wireframes.png"><strong>Team Wireframe</strong></a>
1. <a href="assets/readme-assets/maxfit-contact-page-wireframes.png"><strong>Contact Wireframe</strong></a>

#### 5. The Surface Plane ####

Having completed the previous 4 stages in the UX design process, I moved on to making decisions around the design and styling of the website. The Surface Plane focuses on the styling of images, backgrounds, fonts, and colours used on a website. The details of these decisions are listed here;

1. Colours - The color scheme for the website was chosen from a selection of colours I considered, using tools on the [Coolors.co](https://coolors.co/) website. The color schemes chosen, along with their HEX values, is shown here;
<img src="assets/readme-assets/maxfit-coolors-palettes.png" width="450">

1. Font - I used the Google Fonts website to help me decide on a font to use on the MAXFIT website. I wanted something simple yet strong at the same time - not too light, not too bold. I decided upon a Font called Nunito Sans. An example of it can be seen here;   
<img src="assets/readme-assets/maxfit-font-nunito-sans.png" width="220">

1. Images - I mainly used photos taken from the [Unsplash.com](https://unsplash.com/) website. On Unspalsh.com I was able to create collections of phtotos for each of the services and classes which I wanted a gallery for. E.g. a selection for yoga, pilates, personal training etc.

1. Icons - I used Font Awesome to add icons to various page and section headings. The footer navigation list had icons which matched the icon found on each page heading. I also added a Font Awesme Favicon to the page headers.

1. Galleries - I decide to use Bootstrap Modals as containers for my Carousel Galleries.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 3. <a name="development-process">Development Process</a> ##

I drew up a process to follow for developing the MAXFIT website. This is listed in sequence below.

1. Design - I firstly designed the site based on the Client/User Stories requirements, by getting ideas from fitness club/gym websites, and by creating wireframes/sketches.
1. Structure - I then wrote the HTML code for all pages including; navigation, footers, sections, galleries, forms, iframes.
1. Content - I then added text content to sections (lorem ipsum/placeholder text), and images to galleries. 
1. Style - I then added colours and fonts and wrote CSS rule sets and media queries in order to style the website.
1. Responsive - I made sure all texts/headings, images, and container elements transform approprately and look good when viewed on different devices such as: mobile phones, tablets, laptops, large screen computers (PC's), and large TV's. 
1. Review - I did a last review of all code (formatting, besutifying etc) and content, fixing anys bugs/typo's etc as I did so.
1. Testing - And finally I validated my HTML and CSS code, and tested functionality of site elements across a range of different devices and browsers.


#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 4. <a name="website-features">Website Features</a> ##
* Bootstrap navigation bar
* Image Carousel 
* Gallery Modals
* Free Trial signup form
* Free Consultation call-back form
* Membership sign-up form
* Bootstrap responsive grid
* Social Links in footer
* Navigation links in Footer
* Accordian on Classes page
* Google map on Contact page
* Google Analytics

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 5. <a name="technologies-used">Technologies Used</a> ##

<img src="assets/readme-assets/maxfit-tech-logos-readme-2.png" width="430">

I used the following technologies, services, and devices to develop, style, deploy, and test the MAXFIT website;
<br>
* HTML5 - The site was develop using HTML5 markup language.
* CSS3 - The site was styled and in some cases made responsive using CSS3.
* Bootstrap - I used the Bootstrap framework for implementing some sections and features.
* GitHub - I set up a free repository on GitHub.com to maintain a master of all website files, content, and resources.
* GitPod - I used the free GitPod.io Integrated Development Environment to write and develop the code for the website.
* Github Pages - I used the free GitHub Pages to deploy/publish the live website on the web.
* Balsamiq - I used the Balsamiq application to create the website sitemap and webpage wireframes.
* Responsive Viewer - I used a Chrome Browser Extension called Responsive Viewer to emulate the presentation of the website on multiple device sizes and types.
* Apple Preview - I used the Apple Preview image editor application to crop and resize photo's and images. 
* Apple Pages - I used the Apple Pages word processor to manage and edit text content for the website. 
* Apple Hardware - I used a MacBook Pro to develop the site. I also used an Apple iPhone, Apple TV, and Apple iPad for testing the website.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 6. <a name="testing">Testing</a> ##

* Test navigation, assets, and external links in README.md

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 7. <a name="deployment">Deployment</a> ##

This site was developed by firstly setting up a GitHub repository to store the website files. GitHub is a free online code hosting platform for websites or web applications, which enables version control and collaboration during the development of a project. A repository on GitHub containes all of a project's files and each file's revision history. You can learn more about GitHub and repositories here: [Click here to go to GitHub](https://docs.github.com/en/free-pro-team@latest/github)

I used the online GitPod Integrated Development Environment (or GitPod IDE) to write the site code. Once I was happy with a section of code I commited or saved that to the working version of the website on GitPod. I then 'pushed' those changes from the GitPod IDE to my GitHub repository where the master set of files was updated. You can learn more about GitPod: [Click here to go to GitPod](https://docs.github.com/en/free-pro-team@latest/github)

Early on in the development process I also deployed the website to a live web address using GitHub Pages. GitHub pages is a free static-site hosting service. It takes HTML, CSS, and JavaScript files directly from a GitHub repository and publishes a website with them. Once setup, any changes you make on your IDE which are subsequently 'pushed' to your GitHub repository, are automatically updated on GitHub Pages too. 

Here are the steps I took to deploy the website on GitHub Pages;
1. Login to GitHub.
1. Select 'Your Repositores' by selecting the dropdown button on the your account icon at the top right-hand corner of the screen. 
1. When you get to the Your Repositories page, select the project you want to deploy.
1. When in the individual repository page, click on the Settings icon from the lists of options above the repository file list (settings can be seen listed on the far-right of this list).
1. Once in the settings page, scroll down the GitHub Pages section near the bottom of the page.
1. Under the Source section, select the branch of the project you want to deploy from the first dropdown box (normally the master branch).
1. Also under the Source section choose the folder of the files you wnat to deploy (normally '/root').
1. Once you have made your selection, click Save. This will deploy your site to a unique URL. Once the site has been deployed, green text with a tcick mark will appear above the Source secion to notify you that deployment has been successful, and will also show you the URL for the website.

I deployed the website early on in the developmnt process, as it useful to be able to examine the website on various physical devices in its live state. Also, while the GitPod IDE has the ability to show a preview of changes to a project, sometimes that does not pick up or display issues which would appear on a live site. For example, when I deployed my website on GitHub Pages initially, I found that it was not reading my CSS file, so no styling was appearing on the site. The Preview tab in GitPod was reading the CSS file correctly. I found that a typo relating to the CSS file source address in my page headers caused the issue for the deployed site, while GitPod Preview did not pick it up. By having the deployed site up and running, I was able to address and correct the bug early in the development process.

The working version of the MAXFIT website deployed on GitHub Pages can be seen here: [Click here to view deployed website](https://andymc3000.github.io/maxfit-codeinstitute-ms1project-static-gym-website/)

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 8. <a name="credits">Credits</a> ##

1. Coding Websites - W3Schools, Mozila MDN, Bootstrap, GitHub, StackOverflow

1. Colours - I used the Coolors.co website to help me decide on a colour scheme for the webite. This website allows you to create your own colour palettes or to use one of thiers. See more about the Coolors.co palette catalogue and tools here: [Coolors.co](https://coolors.co/). 

1. Font - 

1. Icons -

1. Design Principles - The design of this website employed the principles of 'The 5 Planes of UX design', which was created by Jesse James Garrett in his book; The Elements of User Experience: User-centered Design for the Web (2002). See more at; [Jjg.net](http://www.jjg.net/elements/)
  
1. Company Logo - The Maxfit logo was created using tools on the FreeLogoDesign.org website. See more at; [FreeLogoDesign.org](https://www.freelogodesign.org/)

1. Wikimedia commons - Technology logo's.

1. Text content - I rewordered some of the marketing slogans and texts/descriptions content from Equinox.com and ActiveFitness.ie, and used those on my site.

1. Map - 

1. Website Analytics - 

### Acknowledgements ###

In order to get design ideas, I took inspiration from a number of industry relevant websites.
These websites are;

No. | Business Name | Website | Description
--- | ------------- | ------- | -----------
1 | **The Movement** | [TheMovement.ie](https://www.themovement.ie/) | Single local Gym, Co.Cork, Ireland.
2 | **EQUINOX** | [Equinox.com](https://www.equinox.com/) | 400+ global locations, U.S.-based.
3 | **The Squad** | [TheSquad.ie](https://thesquad.ie/) | City Gym with 3 locations, Cork, Ireland.
4 | **Glofox** | [Glofox.com](https://www.glofox.com/) | Gym manegement and website software company.
5 | **ActiveFitness** | [ActiveFitness.ie](https://activefitness.ie/) | 24-hr Gym with one location, Galway, Ireland.
6 | **The Spencer Health Club** | [TheSpencerHealthClub.com](https://www.thespencerhealthclub.com/) | City Gym one location, Dublin, Ireland.

### Additonal Support ###

I also received help and support from;
* Allen Thomas Varghese - GitHub username: @allentv - my mento at Code Institute. He gave me advice on project planning, VSCode, Wireframing, and requirements.
* Jim - GitHub username: @JimLynx - Code Institute - advice on GitHub/Git/GitPod, milestone project planning, and creating a README.md.
* Anna - GitHub username: @anna_ci - Code Institute - advice with creating a README.md.
* Student Support - Code Institute
* Tutor Support - Code Institute

#### [Back To Top ^ ](#top-of-page) ####

<a name="top-of-page">![M A X F I T Logo created using FreeLogoDesign.org](/assets/readme-assets/maxfit-logo-readme.png)</a>
