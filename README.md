# Star Wars PP1

This Star Wars website is a landing page for people who are interested in learning about Star Wars and gaining a backgound of what the Star Wars Galaxy entails. 

Users of this website will be able to view all the Star Wars movies in chronological order, they can read about the different planets in the Star Wars galaxy, view different phrases that are referenced throughout the films, read about different characters. This site is targeted towards people who want to learn about the Star Wars galaxy.

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
This is a single page website, all information is positioned in a specific order, making it easier for users to navigate the website and consume the content in a precise order. There is a navigation bar at the top of the page that seamlessly scrolls/directes users to each section. This allows users to navigate the site easily.
> As a first time user, I want to navigate throughout the site to find different types of content.

The first section that the user sees is the movie section, which contains information about each Star Wars movie and displays the movies in the timeline they should be watched.
>As a first time user, I want to understand the purpose of the site & learn more about the Star Wars Galaxy.

CSS Media Queries are used to make the website responsive on different screen sizes. All sections are responsive and content styling changes based on the screen size the user is viewing the website with. This is to ensure that the content is readable and not squashed, all images are clear & visible.
>As a first time user, I want to view the website on my Iphone 5.

A section contains a form where users can sign up to the 'Galaxy Club' to stay up-to date with news and events. A user needs to provide their name & email address.
>As a first time user, I want to sign up to the Galaxy Club.

The Galaxy section contains information about important planets in the galaxy and provides the user with insightful information about each planet. Each planet has a cartoon image that represent what it looks like.
>As a first time user, I want to learn about the different planets in the Star Wars Galaxy.

The phrases sections contains phrases that are used throughout the Star Wars franchise and provides an in-depth description of what each phrase means.
>As a first time user, I want to learn about the different phrases used in the franchise.

The characters section information on the main characters in the galaxy. Each character is represented by a cartoon image to match the design of the planet section.
>As a first time user, I want to learn about the characters.

# Design
## Colour Scheme
The three main colours used throughout the website are blue (#1786eb), yellow (#EEDB00), and grey (#333333) as these colours are similar to the colour scheme in the franchise. Blue is used when ships jump to hyperspace, yellow is used in the Star Wars logo, and grey matches the dark theme seen throughout the film.

## Imagery

## Wireframes

# Limitations



# **Features**


## Navigation
* At the top of the page, the navigation bar shows the websites logo in the left corner (lightsaber & deathstar)
* The other navigation links are positioned to the right: Movies, Galaxy, Characters which link to different sections on the same page.
* The navigation has background colour that makes it visible over the dark body image
* The navigation indicates the websites topic and makes the different sections of information easy to find


![image](https://user-images.githubusercontent.com/83119583/178244413-668ca36f-e413-4560-845e-72d604536f45.png)


## The Movie Section
* The movie section gives the user details about each Star Wars move, the title, the year it was released and the director
* The movies are displayed in chronological order, to follow the story & provide links to a streaming service to watch the movie

![image](https://user-images.githubusercontent.com/83119583/178244848-b8e3d31b-79aa-4327-b125-2eeea541da97.png)


## The Galaxy Section
* The galaxy section gives the user details about each planet in the Star Wars galaxy, an icon based on the design of is planet is there and and some information about the planet
* This section shows some phrases that are used in the Star Wars galaxy and provides a description of each phrase

![image](https://user-images.githubusercontent.com/83119583/178245202-fc41f22b-2af6-4425-b144-118b0db6dc7c.png)

![image](https://user-images.githubusercontent.com/83119583/178245360-d24c08fa-ac14-434c-9e96-86ac8160195f.png)



## The Characters Section
* The characters section has a slideshow of each character with a cartoon image. When the user hovers on a character image, a brief description of the character is displayed


![image](https://user-images.githubusercontent.com/83119583/178247038-66cdf9d6-a2b1-49a6-b4a9-10c88a664d02.png)

## The Footer
* The footer section includes links to the relevant social media sites for Star Wars. The links will open a new tab to allow easy navigation for the user.
* The footer encourages users to keep up to date and connected via social media

![image](https://user-images.githubusercontent.com/83119583/178248935-4544482c-1534-47c6-ac10-2f2bd27d97bd.png)



# **Testing**
## Validator Testing
* To verify that the HTML code written to the best standard, I conducted validator
testing with the W3C Markup Validator and no errors or warning were identified in the HTML code.

![image](https://user-images.githubusercontent.com/83119583/178250184-a5b736d1-7aee-488a-973a-e85f46fd0659.png)

* CSS styling was validated using the W3C CSS Validation Service to ensure the code was written to the expected standard. No errors were found when passing through the W3C CSS validator.

![image](https://user-images.githubusercontent.com/83119583/178250682-ff5a49b3-6ad5-4122-9fc8-eeb1071273fe.png)


## Responsive Testing
* The website was tested on several devices and screen sizes to ensure it was responsvie regardless of the screen size. It has been tested on desktop, Ipad Mini, Ipad Air, Iphone 5, Samsung Galaxy S8+, Iphone X, Iphone SE. Mobile devices have been tested in portrait and landscape mode. The site has been tested in chrome & edge browsers.

## Lighthouse Testing
* The Lighthouse tool in Chrome DevTools is used to test a websites performance & accessibility. It is an open-source automated tool sued to improve the quality of webpages. 
When I tested my website, an audit report was returned indicating that my website has high performance and is accessible.


![image](https://user-images.githubusercontent.com/83119583/179273097-8d665435-be27-4959-9ae3-6681349e75e0.png)


## Links Testing
* All links in the navigation bar are working correctly, they scroll down to each section on the page.
* All links in the movie section are working correctly, when clicked the user is directed to a new tab where they can stream the film
* The social media icons are working correctly, when clicked the user is directed to a new tab of that social media platform  

## Manual Testing
| Feature                 | Expect                                                 | Action             | Result            |
| -------------           | -------------                                          | ------------------ | -------           |
| Galaxy Navbar Button    | When clicked the page scrolls to the 'galaxy' section  | Clicked 'Galaxy' button on navbar      | Page scrolled to 'galaxy' section             |
| Movie Grid Link         | When a movie block is clicked, a streaming service to watch the movie clicked is opened in another tab | Clicked 'Solo Story' movie block  | The link opened in a new tab on the correct site |
| Phrase Hover Effects    | When a phrase is hovered on, information about the phrase is displayed  | Used mouse to hover on 'lightsaber' phrase      | Lightsaber information displayed on hover            |
| Movie Hover Effects    | When a movie is hovered on, the box should zoom in  | Used mouse to hover on 'Attack Of The Clones' movie block      | Box zoomed in            |
| Responsive Navbar    | When the screen size is reduced, the logo should not be visible and the nav elements should be aligned beside eachother | Used ChromeDev Tools to reduce page size to 320px      | Logo was not visible, nav elements and navbar was responsive            |
| Character Hover Effects    | When a character is hovered on, information about the character is displayed  | Used mouse to hover on 'R2D2 character' card      | R2D2 character information displayed on hover hover            |
| Character Scrollbar    | When dragged the character section scrolls diagonally to display more characters  | Used mouse to drag the scrollbar phrase      | Character section scrolls diagonally & displayed more characters            |

# **Bugs**
## Fixed Bugs
* When reducing the screen size, the movie section was not responsive and the movie boxes would squash together instead of spacing and starting a new line. To fix this error I refactored the html code and removed the unique classes each movie had and replaced with one global container with divs. I added flex properties to this container and added the flex-wrap property which makes the divs inside the container responsive
* When reducing the screen size, the navbar elements would stack on top of eachother underneath the logo. To fix this error I added a media query when the screen size is equal to or less than 720px. When the screen is this size, I add a display:none property to the logo for more spacing. I also reduce the margin and padding to make the elements align beside eachother neatly.
* When reducing the screen size, the content inside the phrase cards was overflowing outside the container. To fix this bug, I added a media query when the screen size is equal to or less than 500px. In this query, I changed to opacity to 1 so the content is displayed and the hover effects are redundant.

## Technologies Used
* [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 
* [Google Fonts](https://fonts.google.com/)
* [Github](https://github.com/emmaC11/PP1-starwars)
* [GitPod](https://gitpod.io/)
* [Font Awesome](https://fontawesome.com/)
* [Flaticon](https://www.flaticon.com/free-icons/star-wars)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator)
* [W3C HTML Validator](https://validator.w3.org/#validate_by_input)

# **Credits/References**
## Content & Media
* I took inspiration from this [Star Wars Kids](https://www.starwarskids.com/) website. All of the images & content from the character section is from this section.
* All of the images & content for the movie section is from [Disney Plus](https://www.disneyplus.com/en-gb/home)
* I used a generic starry night image from twitter for the background.
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



## Deployment
* this is the design section


