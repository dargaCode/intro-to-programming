Rubric details for the Portfolio Project and the Open API Project can be seen below.  Be sure both your projects meet the requirements specified for each:

## Portfolio Project
<details>
<summary>Click here to expand the Portfolio Project rubric</summary>
<br>
<h3>General</h3>
<ul>
<li>Project is published on a public GitHub repository</li>
<li>Code executes without errors in the browser</li>
</ul>

### Project Structure
 - [ ] README.md (_NOTE:_ this file is typically used to explain how someone can run your code, but it does not need to contain this content for your final project to be acceptable)
 - [ ] index.html
 - [ ] css folder
   - [ ] index.css
 - [ ] js folder
   - [ ] index.js 
 - [ ] (OPTIONAL) images folder

#### index.html
 - [ ] include proper boilerplate code
 - [ ] (OPTIONAL) use a font-family or Google fonts
 - [ ] index.css and index.js file should be properly linked to this file
 - [ ] level 1 heading with student's name
 - [ ] navigation with working internal links to the following sections:
    - [ ] About
    - [ ] Experience
    - [ ] Skills
    - [ ] Projects
    - [ ] Leave a Message
    - [ ] (OPTIONAL) Connect or Contact Me section to contain email and social media links
 - [ ] (OPTIONAL) sticky/fixed navigation that stays in place when user scrolls down on the page
 - [ ] (OPTIONAL) dark mode toggle switch to change coloring of background and text between default and dark mode
 - [ ] (OPTIONAL) navigation converted to a hamburger menu on smaller devices via media queries
###### About Section
 - [ ] level 2 heading
 - [ ] one or more paragraphs of text
 - [ ] (OPTIONAL) your photo with alt attribute for accessibility 
###### Experience Section
 - [ ] level 2 heading
 - [ ] list of previous work or experience or one or paragraphs of related experiences if student has no previous work experience)
 - [ ] if listing experience, this should be styled in grid or flexbox layout
###### Skills Section
 - [ ] level 2 heading
 - [ ] list of skills, inserted using JavaScript from the index.js file
 - [ ] list should be styled in a grid or flexbox layout
###### Projects Section
 - [ ] level 2 heading
 - [ ] list of GitHub repositories, fetched using the GitHub API and inserted using JavaScript from the index.js file 
 - [ ] (OPTIONAL) each GitHub repository name is a clickable link that takes the user to that repository
 - [ ] (OPTIONAL) display additional information about each of the repositories (examples: created date, description, etc.)
 - [ ] (OPTIONAL) customize the styling of your projects list (cards or use of flexbox or grid for examples)
###### Leave a Message Section (Form and Messages List)
 - [ ] level 2 heading for form
    - [ ] Name, Email Address, and Message fields
    - [ ] Submit button
    - [ ] event listener that adds the form field inputs to the messages section
 - [ ] level 2 heading for messages
    - [ ] list of messages (once the form has been given inputs and submit button clicked) styled in a grid of flexbox layout
      - [ ] Each message item should have the following:
        - [ ] Name of message author as a clickable link to email the author at the email address they provided in the form
        - [ ] Message text
        - [ ] Remove button to delete the message from the list of messages
        - [ ] (OPTIONAL) Edit button for user to change one (or more) of the form inputs (name, email, message)
    - [ ] (OPTIONAL) conditionally render (meaning hide/display) the level 2 heading and section content depending on whether or not there are messages
###### (OPTIONAL) Connect or Contact Me
_NOTE:_ If you do not have a Connect or Contact Me section, your links should be in the footer of your page as icons/images
 - [ ] clickable link to email the student 
 - [ ] at least two social media links to the student's profile pages (examples: GitHub, LinkedIn, twitter, instagram, etc.)
 - [ ] (OPTIONAL) use icons or images in place of text string links for your email and 2+ social media links
###### Footer
 - [ ] Copyright logo, current year, and student's name inserted using JavaScript from the index.js file
 - [ ] Email and 2+ social media icon/image links (if the page does NOT have a Connect or Contact Me section)

#### index.js
 - [ ] Comments in code as appropriate (to notate what sections of code are used for)
 - [ ] Sections of code to accomplish the following:
   - [ ] Insert the copyright logo, current year, and student's name in the footer of index.html
   - [ ] Using an array, insert the array items as a list of skills in the skills section of index.html
   - [ ] Handle the event listener on the message form to insert the following into the messages section:
     - [ ] convert form inputs into the author's name as a clickable link 
     - [ ] display their message and 
     - [ ] provide a remove button to delete the message
     - [ ] (OPTIONAL) provide an edit button to change one or more form fields
     - [ ] (OPTIONAL) conditionally render the messages header and section of index.html (show it if there are messages, hide it if none)
   - [ ] Using API fetch, insert the names of your GitHub repositories in the projects section of index.html
     - [ ] (OPTIONAL) provide additional information about each repository
     - [ ] (OPTIONAL) make the repository names clickable links that redirect the user to that repository page

#### index.css
 - [ ] (Optional) Comments in code as appropriate (to notate what sections of code are for)
 - [ ] At least two media queries
   - [ ] In each media query there should be at least 2 property changes to at least 3 html elements
 - [ ] Flexbox (or Grid) used to format the layout of the Experience and Connect sections _(NOTE: If you are using social media icons in your footer in place of a Connect section, you should use Flexbox or Grid to format the layout of your icons in the footer)_

#### (OPTIONAL) images folder
 - [ ] If you've elected to use images in your portfolio, be sure to have an images folder at the root level of your repository (same level as your index.html and README.md files).  All your images should go in this folder
 - [ ] Make sure images used in your html or css files are properly linked to the image inside your images folder
 - [ ] Remember to use alt for any images so there will be helper text if the image is not displayed properly

#### Styling
Everyone's style is different and we encourage students to let the style fo their site represent them.  That being said, there are some general style guidelines we encourage you to follow:
 - [ ] Remember to have appropriate contrast to your site (don't use a dark font on a dark background
 - [ ] You should not need to horizontally scroll to see your site content on any device (mobile, tablet, or desktop)
 - [ ] Watch out for font sizes on smaller devices.  The screen is smaller, but the font size should not be small also.  This is also true for form input fields/buttons, a user would need to tap on it with a finger to get focus on the input to type, don't make it too small that their device can't recognize what they're trying to tap on.
</details>

## Open API Project
<details>
<summary>Click here to expand the Open API Project rubric</summary>
<br>
Use one of the following open source APIs to create a site that accesses a minimum of 2 endpoints.  (Example: if using the weather app, you could display (1) the temperature and (2) the weather condition).  

### Open Source API options:
* [Open-Meteo](https://open-meteo.com/) – a weather API
* [Swapi.Tech](https://www.swapi.tech/) – an API about Star Wars films
* [Marvel](https://developer.marvel.com/) – an API about the Marvel fandom
* [ARTIC](https://api.artic.edu/docs/#introduction) – an art API from the Art Institute of Chicago
* [TheDogAPI](https://thedogapi.com/) or the [TheCatAPI](https://thecatapi.com/) – APIs about (you guessed it!) Dogs or Cats
* [SampleAPIs](https://sampleapis.com/api-list/coffee) – an API for coffee lovers

Be sure to satisfy the below requirements in your Open API Project:

### STRUCTURE:
 - [ ] A public GitHub repository containing your project
 - [ ] An HTML document for the page
 - [ ] A CSS document to style the HTML page
 - [ ] A JavaScript file that retrieves data from one of several public API sources to display the data on your HTML page
 - [ ] A README file that includes the instructions for running the webpage (This does not need to be a live site; you can instruct the user to download and run locally)

### CONTENT:
 - [ ] Display the data for at least 2 endpoints in the API
 - [ ] Include navigation from each endpoint’s page to the other (Example: if using the weather app, one navigation link should display the temperature details and the second navigation link should display the weather condition)
 - [ ] Issue new GET requests each time the user click a navigation link, meaning you should have 2 GET requests - one for each navigation, that requests only the needed information (Example: if using the weather app, clicking temperature navigation link should pull only data that allows user to see temperatures and clicking conditions navigation link should pull only data that allows user to see weather conditions)

### FUNCTIONALITY:
 - [ ] Code runs without issues by following the instructions in the README file
 - [ ] Navigation between the different endpoints behaves properly and is not slowed down by requesting more data than needs to be displayed (this is the reason for the 2 separate GET requests)
 - [ ] Code is readable and well structured
 - [ ] If applicable, error cases are appropriately handled
 - [ ] Styling is effective (example: font-sizes are not too small or large, colors are not too dark/light to be easily seen, etc.)
</details>
