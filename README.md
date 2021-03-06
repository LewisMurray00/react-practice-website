## Project Journey:

### Day 1: 
- Set up the react project
- Downloaded the needed packages

### Day 2:
- Created the Navbar and all its functionality
- Added the ablity to use Font awesome for icon images
- Started the button component

### Day 3:
- Button component created, with two different style variables in each array
- Button component styled
- Created a function that is invoked on screen resize that adds and removes a button depending on the screen size

### Day 4
- Navbar styled
- Navbar styled for screens less than 960px
- Added some global styles in the App.css file
- Fixed an issue where the sign up button was appearing on refresh, when screen was small, using useEffect
- Created component folder for the hero section including js and css file

### Day 5
- Hero.js created and coded
- Hero.js Styled
- Created folder for pages
- Created a Home.js component within that pages folder

### Day 6
- Home.js file has the Hero.js imported
- HeroSection.js styling finished
- HeroSection.js has been made responsive
- Created CardItem component folder with JS and CSS file to go in

### Day 7
- Created a cards component folder with the matching js and css files
- CardItem.js set up ready to recieve information from the cards
- Wrote the code for the Cards.js and displayed that on the home page

### Day 8
- Added some CSS for the Cards.js file
- Added some CSS for the CardItem.js file
- Made the CSS files responsive
- Passed props through the CardItem.js into the Cards.js
- Fixed a problem with the images
- Created new pages and linked them with the router
- Created the Footer folder

### Day 9
- Created the Footer.js file and added some JSX to it 
- Created the Footer.css and styled the container

### Day 10
- Finished the JSX for the Footer.js file
- Finished the styling for the Footer.css file
- Made the footer responsive (although not happy may redo)
- Restyled the Navbar

### Day 11/12
- Made some improvements to the Navbar
- Changed the css for a few of the components to suit the style
- Started work on next page

### Day 13/14
- Started editing the our work page
- Creating a slider for images to appear on the page

### Day 14+
- Added slide show to the our work page
- Finished the our work page
- Started the contact us page
- Finished the contact us page
- Started the review page

- Added a ScrollToTop component, allows me to navigate the pages and it will return to the top of the page
- Fixed the contact us page links and reverted back to an anchor tag to allow for external URLs to be reached and a phone number

- Added the about section to the home page and styled it, making it responsive.

- Added the description to the home page

- Added most of the required images and had to add brand new components to combat an issue i couldn't get round ( maybe temporary till i figure it out?)

## Future plans to finish:

- Add the required images

- Restyle the "our work" section (Add a little information section, spread them out a bit more) 

- Add the reviews images and restyle that page
- Ensure the css fits all variety of screens


## React-Router-Dom Guide

- {Link} renders an {a} with a real href
- {BrowserRouter} uses regular URL paths, so web server serves the same page at all URLs that are managed client side
- When a {Switch} (V5) or {Routes} (V6+) is rendered it searches through its children elements to find one which path matches the current URL
- {Route} are the children elements of the {Switch/Routes}

## Font-Awesome

- Used this as a way to get the icons for a hamburger bar

## Netlify deployed address

- https://moonlit-biscuit-497934.netlify.app