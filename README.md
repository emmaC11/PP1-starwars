# Star Wars PP1

This Star Wars website is a landing page for people who are interested in learning about Star Wars and gaining a backgound of what the Star Wars Galaxy entails. 

Users of this website will be able to view all the Star Wars movies in chronological order, they can read about the different planets in the Star Wars galaxy, view different phrases that are referenced throughout the films, read about different characters. This site is targeted towards people who want to learn about the Star Wars galaxy.

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

## Technologies used
* this is the technologies used section

## User Stories
* this is the user stories section

## Design
* this is the design section


