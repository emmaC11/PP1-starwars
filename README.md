# Star Wars PP1

This Star Wars website is a website for people who are interested in learning about Star Wars and gaining a backgound of what the Star Wars Galaxy entails. 

Users of this website will be able to view all the Star Wars movies in chronological order, they can read about the different planets in the Star Wars galaxy, view different phrases that are referenced throughout the films and read about different characters. This site is targeted towards people who want to learn about the Star Wars galaxy.

# **Table Of Contents**
* [User Experience & Design](#user-experience--design)
    * [User Stories](#user-stories)
        * [First Time Visitor Goals](#first-time-visitor-goals)
        * [Structure](#structure)
    * [Design](#design)
        * [Colour Scheme](#colour-scheme)
        * [Typography](#typography)
        * [Imagery](#imagery)
        * [Wireframes](#wireframes)
* [Features](#features)
    * [Navigation](#navigation)
    * [Movie Section](#the-movie-section)
    * [Galaxy Section](#the-galaxy-section)
    * [Characters Section](#the-characters-section)
    * [Galaxy Club Form](#galaxy-club-form)
    * [Footer](#the-footer)

* [Testing](#testing)
    * [Validator Testing](#validator-testing)
    * [Responsive Testing](#responsive-testing)
    * [Lighthouse Testing](#lighthouse-testing)
    * [Links Testing](#links-testing)
    * [Manual Testing](#manual-testing)
    * [Bugs](#bugs)

* [Technologies Used](#technologies-used)
* [Deployment](#deployment)
    * [Project Creation](#project-creation)
    * [GitHub Pages](#deployment-to-github-pages)
    * [Run Locally](#run-locally)

* [Credits/References](#creditsreferences)
    * [Content & Media](#content--media)
    * [Code](#code)
    * [Achknowledgements](#achknowledgements)


# **User Experience & Design**

# User Stories
## First Time Visitor Goals
* As a first time user, I want to understand the purpose of the site & learn more about the Star Wars Galaxy.
* As a first time user, I want to navigate throughout the site to find different types of content.
* As a first time user, I want to view the website on my Iphone 5.
* As a first time user, I want to sign up to the Galaxy Club.
* As a first time user, I want to learn about the different planets in the Star Wars Galaxy.
* As a first time user, I want to learn about the different phrases used in the franchise.
* As a first time user, I want to learn about the characters.

## Structure
This is a single page website, all information is positioned in a specific order, making it easier for users to navigate the website and consume the content in a precise order. There is a navigation bar at the top of the page that seamlessly scrolls/directs users to each section. This allows users to navigate the site easily.
> As a first time user, I want to navigate throughout the site to find different types of content.

The first section that the user sees is the movie section, which contains information about each Star Wars movie and displays the movies in the timeline they should be watched.
>As a first time user, I want to understand the purpose of the site & learn more about the Star Wars Galaxy.

CSS Media Queries are used to make the website responsive on different screen sizes. All sections are responsive and content styling changes based on the screen size the user is viewing the website with. This is to ensure that the content is readable and not squashed, all images are clear & visible.
>As a first time user, I want to view the website on my Iphone 5.

A section contains a form where users can sign up to the 'Galaxy Club' to stay up-to date with news and events. A user needs to provide their name & email address. As JavaScript is not part of this project stack, data submitted within the form is not stored.
>As a first time user, I want to sign up to the Galaxy Club.

The Galaxy section contains information about important planets in the galaxy and provides the user with insightful information about each planet. Each planet has a cartoon image that represent what it looks like.
>As a first time user, I want to learn about the different planets in the Star Wars Galaxy.

The phrases sections contains phrases that are used throughout the Star Wars franchise and provides an in-depth description of what each phrase means.
>As a first time user, I want to learn about the different phrases used in the franchise.

The characters section provides information about main characters in the galaxy. Each character is represented by a cartoon image to match the design of the planet section.
>As a first time user, I want to learn about the characters.

# Design
## Colour Scheme
The three main colours used throughout the website are blue (#1786eb), yellow (#EEDB00), and grey (#333333) as these colours are similar to the colour scheme in the franchise. Blue is used when ships jump to hyperspace, yellow is used in the Star Wars logo, and grey matches the dark theme seen throughout the film.

## Typography
The headers throughout the website are using the <strong>Righteous</strong> font and the main body text is using the <strong>Kanit</strong> font.

## Imagery
All images are related to the Star Wars Franchise and the website has a cartoon branding approach. The logo image is a lightsaber and a death star which represents the republic and the sith, the story arc of the film. The size & placement of the logo image varies on screen size. All planet images and character images are cartoons to capture visual interest of the user and keep a consistent theme. Images used in the movie section are poster images that were used for press when the movies were released. 

## Wireframes
![image](https://user-images.githubusercontent.com/83119583/179348538-61e73435-c2bb-445b-a82f-1415022af236.png)
![image](https://user-images.githubusercontent.com/83119583/179348568-59af0e06-65eb-491e-8aa9-ddd2ed88628d.png)



# **Features**


## Navigation
* At the top of the page, the navigation bar shows the websites logo in the left corner (lightsaber & deathstar).
* The other navigation links are positioned to the right: Movies, Galaxy, Characters which link to different sections on the same page.
* The navigation has a grey background colour to make it visible over the dark body image.
* The navigation indicates the websites topics and makes the different sections of information easy to locate.


![image](https://user-images.githubusercontent.com/83119583/178244413-668ca36f-e413-4560-845e-72d604536f45.png)


## The Movie Section
* The movie section gives the user details about each Star Wars movie - the title, the year it was released and the director.
* The movies are displayed in chronological order, to follow the story & links are provided to a streaming website to watch the movie.

![image](https://user-images.githubusercontent.com/83119583/178244848-b8e3d31b-79aa-4327-b125-2eeea541da97.png)


## The Galaxy Section
* The galaxy section gives the user details about each planet in the Star Wars galaxy, an icon based on the design of the planet is there and some information about the planet.
* This section shows some phrases that are used in the Star Wars galaxy and provides a description of each phrase.

![image](https://user-images.githubusercontent.com/83119583/178245202-fc41f22b-2af6-4425-b144-118b0db6dc7c.png)

![image](https://user-images.githubusercontent.com/83119583/178245360-d24c08fa-ac14-434c-9e96-86ac8160195f.png)



## The Characters Section
* The characters section has a slideshow of each character with a cartoon image. When the user hovers on a character image, a brief description of the character is displayed.


![image](https://user-images.githubusercontent.com/83119583/178247038-66cdf9d6-a2b1-49a6-b4a9-10c88a664d02.png)

## Galaxy Club Form
* The sign up form allows user to sign up to the Galaxy club which keeps them up-to date with the latest Star Wars news & events. When the form is submitted, the user is brought to a page where they have the option to return to the website. Form validation is implemented, the form cannot be submitted if the fields are left empty and if the user does not provide valid syntax for an email address.

![image](https://user-images.githubusercontent.com/83119583/179349155-f092321d-7741-4ef4-be0b-70ecd3ed85bd.png)
![image](https://user-images.githubusercontent.com/83119583/179349132-d0091bd5-74f5-476b-b195-231a0b408d62.png)

## The Footer
* The footer section includes links to the relevant social media sites for Star Wars. The links open a new tab to allow easy navigation for the user.
* The footer encourages users to keep up to date and connected via social media.

![image](https://user-images.githubusercontent.com/83119583/178248935-4544482c-1534-47c6-ac10-2f2bd27d97bd.png)



# **Testing**
## Validator Testing
* To verify that the HTML code written to the best standard, I conducted validator
testing with the W3C Markup Validator. I fixed the errors and warnings and currently there are no errors or warnings in the HTML code.

![image](https://user-images.githubusercontent.com/83119583/178250184-a5b736d1-7aee-488a-973a-e85f46fd0659.png)

* CSS styling was validated using the W3C CSS Validation Service to ensure the code was written to the expected standard. No errors were found when passing the code through the W3C CSS validator.

![image](https://user-images.githubusercontent.com/83119583/178250682-ff5a49b3-6ad5-4122-9fc8-eeb1071273fe.png)


## Responsive Testing
* The website was tested on several devices and screen sizes to ensure it was responsvie regardless of the screen size. It has been tested on desktop, Ipad Mini, Ipad Air, Iphone 5, Samsung Galaxy S8+, Iphone X, Iphone SE. Mobile devices have been tested in portrait and landscape mode. The site has been tested in Chrome, Edge, FireFox & Brave browsers.

## Lighthouse Testing
* The Lighthouse tool in Chrome DevTools is used to test a websites performance & accessibility. It is an open-source automated tool used to improve the quality of webpages. 
When I tested my website, an audit report was returned indicating that my website has high performance and is accessible.


![image](https://user-images.githubusercontent.com/83119583/179273097-8d665435-be27-4959-9ae3-6681349e75e0.png)


## Links Testing
* All links in the navigation bar are working correctly, they scroll down to each section on the page.
* All links in the movie section are working correctly, when clicked the user is directed to a new tab where they can stream the film.
* The social media icons are working correctly, when clicked the user is directed to a new tab of that social media platform.
* The button to return to the website when a form is submitted is functional.

## Manual Testing
| Feature                 | Expect                                                 | Action             | Result            |
| -------------           | -------------                                          | ------------------ | -------           |
| Galaxy Navbar Button    | When clicked the page scrolls to the 'galaxy' section  | Clicked 'Galaxy' button on navbar      | Page scrolled to 'galaxy' section             |
| Movie Grid Link         | When a movie block is clicked, a streaming service to watch the movie is opened in another tab | Clicked 'Solo Story' movie block  | The link opened in a new tab on the correct site |
| Phrase Hover Effects    | When a phrase is hovered on, information about the phrase is displayed  | Used mouse to hover on 'lightsaber' phrase      | Lightsaber information displayed on hover            |
| Movie Hover Effects    | When a movie is hovered on, the box should zoom in  | Used mouse to hover on 'Attack Of The Clones' movie block      | Box zoomed in            |
| Responsive Navbar    | When the screen size is reduced, the logo should not be visible and the nav elements should be aligned beside eachother | Used ChromeDev Tools to reduce page size to 320px      | Logo was not visible, nav elements and navbar was responsive            |
| Character Hover Effects    | When a character is hovered on, information about the character is displayed  | Used mouse to hover on 'R2D2 character' card      | R2D2 character information displayed on hover hover            |
| Character Scrollbar    | When dragged the character section scrolls diagonally to display more characters  | Used mouse to drag the scrollbar phrase      | Character section scrolls diagonally & displayed more characters            |
| Form Submission   | When the submit button is clicked, the user is brought to a new page  | Typed 'emma' in the first name input field. Typed 'c' in the last name input field. Typed 'test@test' in the email field. Clicked the submit button     | Brought to a new page, form submitted successfully            |
| Form Validation - email    | When an invalid email is entered, the form does not submit  | Typed 'emma' in the first name input field. Typed 'c' in the last name input field. Typed 'test' in the email field.      | Form did not submit, received pop up warning that email was invalid           |
| Form Validation - empty fields  | When a field is left blank, the form does not submit   |  Typed 'c' in the last name input field. Typed 'test@test' in the email field.    | Form did not submit, received pop up warning that the field is required            |



## Bugs Identified During Testing
* When reducing the screen size, the movie section was not responsive and the movie boxes would squash together instead of spacing and starting a new line. To fix this error, I refactored the html code and removed the unique classes each movie had and replaced with one global container with divs. I added flex properties to this container and added the flex-wrap property, which makes the divs inside the container responsive.
* When reducing the screen size, the navbar elements would stack on top of eachother underneath the logo. To fix this error, I added a media query when the screen size is equal to or less than 720px. When the screen is this size, I add a display:none property to the logo for more spacing. I also reduce the margin and padding to make the elements align beside eachother neatly.
* When reducing the screen size, the content inside the phrase cards was overflowing outside the container. To fix this bug, I added a media query when the screen size is equal to or less than 500px. In this query, I changed to opacity to 1 so the content is displayed and the hover effects are redundant.
* When viewing the website on a large monitor at work, the site was not responsive. To fix this bug, I updated the css measurements from pixels to rem, making the site more reliable and responsive regardless of screen size.
* When validating my html code, I used several h1 tags throughout the website - this is not best practise. I refactored my code to only have one h1 tag that is visible to screen-readers only to ensure my site is acessible to everyone.
* When viewing the website in edge and interent explorer, the background image was not rendering. After some investigation, I discovered edge and interent explorer cannot render AVIF files. To fix this bug, I converted the AVIF background image to a JPG file.
* When testing form-submit.html with the W3c HTML Validator, I had an error as I had an 'a' tag nested inside in a button. To fix this bug, I removed the button tags, updated the selector in the css file and removed the default text-underline styling.

# Technologies Used
* [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 
* [Google Fonts](https://fonts.google.com/)
* [Github](https://github.com/emmaC11/PP1-starwars)
* [GitPod](https://gitpod.io/)
* [Font Awesome](https://fontawesome.com/)
* [Flaticon](https://www.flaticon.com/free-icons/star-wars)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator)
* [W3C HTML Validator](https://validator.w3.org/#validate_by_input)
* [Image Convertor](https://www.freeconvert.com/)

# **Deployment**
## Project Creation
This project was created using Gitpod, Gitpod provides prebuilt development environments with a variety of IDEs. 

To use Gitpod, install the Gitpod extension on either Firefox or Chrome. When the extension is installed, it adds a green Gitpod button to Github, where we can click to create a workspace in Gitpod.

For this project, I used the Visual Studio IDE. I used the prebuilt environment provided by [Code Institue](https://github.com/Code-Institute-Org/gitpod-full-template) to start this project. I clicked the 'use this template' button and named my repository 'PP1-starwars'. I then created a Gitpod workspace by clicking the green gitpod button in my [PP1-starwars](https://github.com/emmaC11/PP1-starwars) repository.

I used the following commands throughout the development of this project:
* **python3 -m http.server**  - This command runs a local webserver to view the project.
* **git add .** - This command adds all the changes that have been in the working directory to the staging area. Ready to be committed.
* **git commit -m ""** - This command is used to write descriptive messages of what changes have been made to the code and commits the changes to the local repository.
* **git push** - This command pushes all the committed changes to the Github repository.

## Deployment to GitHub Pages
1. Navigate to [GitHub Repository](https://github.com/emmaC11/PP1-starwars)
2. Click the 'Settings' tab.
3. Scroll down to the 'pages' tab on the navigation bar.
4. Open the 'Pages' tab.
5. Select 'main' branch as the source.
6. Click 'save'.
7. Click the link provided to go to the deployed website.
8. The live link can be found here - [PP1-starwars](https://emmac11.github.io/PP1-starwars/).

## Run Locally
1. Locate the [GitHub Repository](https://github.com/emmaC11/PP1-starwars).
2. Click the 'Code' dropdown button.
3. Copy the git URL from the HTTPS text bar.
4. Open a terminal window and locate the directory where you want to store the project.
5. Type the 'git clone' command in the terminal, then paste the git URL. Click return on your keyboard to enter the command.
6. A clone of the project will be created locally on your machine.
**Note** - git commands only work if git is installed on your machine. Find installation documentation [here](https://git-scm.com/).

# **Credits/References**
## Content & Media
* I took inspiration from this [Star Wars Kids](https://www.starwarskids.com/) website. All of the images & content from the character section is from this website.
* All of the images & content for the movie section is from [Disney Plus](https://www.disneyplus.com/en-gb/home)
* I used a generic starry night image from twitter as background image.
* The content for the planet section & the phrases section was taken from [Star Wars Fandom](https://starwars.fandom.com/wiki/Main_Page) & [Star Wars](https://www.starwars.com/)

## Code
* [CSS Tricks](https://css-tricks.com/) helped me add some advanced styling to my website.
* [W3Schools](https://www.w3schools.com/) was referenced throughout my project for different tags & syntax.
* [Youtube](https://www.youtube.com/) was a great source for video tutorials & explanations.
* [Love Running](https://github.com/emmaC11/CI-loverunning-project) was referenced throughout development.
* [MDN Web Docs](https://developer.mozilla.org/en-US/) was referenced for some css attributes.
* [Code Pen](https://codepen.io/) helped me see some sample code and how it worked.
* [Navbar with Logo](https://www.youtube.com/watch?v=x2hdO15luS0) referenced when trying to position logo on navigation bar.
* [Colour Overlay](https://codepen.io/ieatwebsites/pen/wpJmXo) helped me create the blue overlay in the movie section.
* [Media Queries](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) referenced when creating media queries.
* [Hover Cards](https://codepen.io/rafaelavlucas/pen/rQWJYG) referenced when creating phrase cards.
* [Masonry Grid](https://www.youtube.com/watch?v=icnZSJbNsEM) referenced when creating the planets section.
* [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) helpful reference when working with flexbox.
* [Text Overlay](https://codepen.io/ArnaudBalland/pen/vGZKLr) referenced when adding the text overlay to the character section.
* [Scrollbar Styling](https://www.w3schools.com/howto/howto_css_custom_scrollbar.asp) referenced when styling the scollbar in the characters section.
* [Image Scroller](https://css-tricks.com/css-only-carousel/) referenced when creating the image scroll for the characters section.

## Achknowledgements

I would like to thank my mentor Ronan for his guidance throughout my project.
I would also like to thank Simen for his excellent masterclasses.





