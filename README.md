  ![Site Logo](/static/media/logo2_hydent.png)
## Table of Contents
* [Purpose](#Purpose)
* [Social](#Social)
* [Features](#Features)
    * [Existing](#Existing)
        * [Navigation Bar](#Navigation-Bar)
        * [The Hero Image](#The-Hero-Image)
        * [Main Section](#Main-Section)
        * [Footer](#Footer)
        * [Galleries](#Galleries)
        * [Form](#Form)
        * [Visited Links](#Visited)
    * [Left to Implement](#Left-to-Implement)
* [Technologies](#Technologies)
* [User Experience Design (UX)](#User-Experience-Design)
    * [Business Goals](#Business-Goals)
    * [User Goals](#User-Goals)
        * [First Time Visitor](#First-Time-Visitor)
        * [Returning Visitor](#Returning-Visitor)
        * [Frequent User](#Frequent-User)
    * [Design](#Design)
        * [Color Scheme](#Color)
        * [Typography](#Typography)
        * [Wireframes](#Wireframes)
* [Limitations](#Limitations)
* [Testing](#Testing)
    * [Test Results](#Test-Results)
        * [Validators](#Validators)
        * [Lighthouse](#Lighthouse)
        * [Devices](#Devices)
    * [Testing Issues](#Testing-Issues)
* [Deployment](#Deployment)
    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Github-Pages)
    * [Locally](Locally)
    * [Commands](Commands)
* [Credits](#Credits)
    * [Content](#Content)
    * [Media](#Media)
    * [Acknowledgements](#Acknowledgements)
* [Comments](#Comments)

# Purpose
The idea behind this site is to bring conscience about the importance of oral hygiene by using some educational videos and also through an extensive portfolio of products, selected from available distributors and more important, with technical advice from a dentist to ensure they are appropriate as the best option.
The portfolio of dental products will provide additional information about each item and then, if the user is registered it will be possible to buy online or see more detailed information otherwise, online purchasing will not be possible but some basic information still stay available. 
This site was built with basic functionality and navigation but soon, more advanced features will be deployed such as a blog to put questions regarding any available products or request for some technical advise, a points scheme for discount on products if a user has a good record of purchasing, but all these features only if the user is registered. 

The live website can be found [here](https://pp5-hydent-fe70bfaafea4.herokuapp.com/). 
[here](https://8000-baptistapaulo-pp5-s6ai9ozvtd.us2.codeanyapp.com/).

[Table-of-Contents](#Table-of-Contents)

# Social
Facebook

The Facebook page can be found [here](https://www.facebook.com/hydental/).

[Table-of-Contents](#Table-of-Contents)

# Features
## Existing
#### Navigation-Bar
![Logo-Menu-Bar](/static/media/) 
#### Main-Section
![main-section](/static/media/) 
#### Footer
![Footer](/static/media/) 
#### Galeries
![Gallery1](/static/media/) 
#### Form
![Form](/static/media/)
#### Admin
![Form](/static/media/site_admin_login_page.PNG) 
#### Heroku App
![Form](/static/media/heroku_initial_working_page.PNG) 

## Left-to-Implement
* A blog 
* A rewards scheme

[Table-of-Contents](#Table-of-Contents)

# Technologies
* Languages
    * HTML5
    * CSS3
    * Python
    * Django
    * Bootstrap
* Frameworks, Libraries and Programs
    * Google fonts
    * Font Awesome
    * GitHub (used to store repositories, files and images pushed from GitPod)
    * GitPod (IDE used to code the website)
    * Git (for version control, commits and push to GitHub)
    * Google Chrome Developer Tools (for checking compatibility, troubleshooting and editing code)
    * TinyPNG (for compression of your WEBP, JPEG and PNG files) [here](https://tinypng.com/).
    * Stackoverflow (for searching on topics related to issues or general queries)
    * W3schools (for HTML/CSS tutorials)

[Table-of-Contents](#Table-of-Contents)

# User-Experience-Design
The UX was deployed and tested for various screen sizes but still needs further testing across different platforms (hardware and software).
This is a section of the deployment still under development.

## Business-Goals
* Provide a central repository of oral dentistry products information.
* Allow users to have access to accurate product details.
* Promote a forum for discussions about oral hygiene.
* Create a points scheme for loyalty users.

## User-Goals
### First-Time-Visitor
* Easy navigation and search for information.
* Site should be visually appealing.
### Returning-Visitor
* Leave some feedback.
* Contact for further information.
### Frequent-User
* Check if any of the topics posted has been commented.
* Find new products.
* Order some products.

## Design
### Color-Scheme
* Predominant colours across all site are light green, light yellow and white.
* Green, black, grey and light blue ocasionaly.

![Color](/static/media/color_scheme.png)

### Wireframes
![wireframe-1](/static/media/) 
![wireframe-2](/static/media/) 
![wireframe-3](/static/media/) 
![wireframe-4](/static/media/) 

[Table-of-Contents](#Table-of-Contents)

# Limitations
This website has not a customized page to acknowledge the submit form so the Code Institute form dump page was used instead.

[Table-of-Contents](#Table-of-Contents)

# Testing
## Test-Results
### Validators
* HTML - Official W3C validator [here](https://validator.w3.org/).
* CSS - Official (Jigsaw) validator [here](https://jigsaw.w3.org/css-validator/).
* Lighthouse – Developer Tools
* Chrome – Developer Tools
* Responsive Design [here](https://ui.dev/amiresponsive).
![responsive](static/)

### Lighthouse
![lighthouse-index-results-performance](/static/media/)   
### Devices
Tested functionality and responsiveness using the below devices and browsers.
* Mobiles
    * Samsung S9
    * Samsung Note
    * Samsung A51
* Laptops
    * HP EliteBook
    * Lenovo ThinkPad
* Browsers
    * Chrome
    * Firefox
    * Edge

## Testing-Issues
* Bugs identified that need to be fixed.
    * main testing and development was performed on Chrome browser and no major issues detected.
    * on Edge and Firefox browsers also no major issues identified.
    * on mobile devices and tablets, pages do not load properly (layout not resized) with impact on UXD but this can be fixed by different media screen sizes in the CSS and with further testing on different platforms.
    * HTML validator has pointed to a few errors (all related to same <p> element) but not all of them were fixed so further testing required to eliminate these errors.
* Further styling and optimization (different screen size) to improve UX requires additional time.

[Table-of-Contents](#Table-of-Contents)

# Deployment
## Project-Creation
This project website was created from scratch, with no forking from any other repositories but based on the initial structure of the Code Institute walkthrough.
Once the structure was in place, then added content and styling as the work was in progress. Some styling was gathered from **Stackoverflow** or **W3schools**.
### Github-Pages
Repository
1. Navigate to the GitHub [Repository:](https://github.com/baptistapaulo/pp5)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages Heading.
1. Select 'Master Branch' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.

### Locally
Clone
1. Navigate to the GitHub [Repository:](https://github.com/baptistapaulo/pp5)
1. Click the Code drop down menu.
1. Either Download the ZIP file, unpackage locally and open with IDE (This route ends here) OR Copy Git URL from the HTTPS dialogue box.
1. Open your developement editor of choice and open a terminal window in a directory of your choice.
1. Use the 'git clone' command in terminal followed by the copied git URL.
1. A clone of the project will be created locally on your machine.

### Fork
Most commonly, forks are used to either propose changes to someone else's project to which you do not have write access, or to use someone else's project as a starting point for your own idea. You can fork a repository to create a copy of the repository and make changes without affecting the upstream repository.
So a fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
1. Navigate to the GitHub Repository you want to fork.
1. On the top right of the page under the header, click the fork button.
1. Create a new fork.
1. This will create a duplicate of the full project in your GitHub Repository.

### Commands
* `CTRL + S` was used to save the page.
* `CTRL + Z` was used to undo a change.
* `python3 -m http.server` was used to view and test site before pushing live.
* `git add` was used to add pages to the stage area.
* `git commit -m "fix: message here"` was used to comit them them to github and provide a relevant message to the changes that had been made.
* `git push` was used to push the changes upto Github for public viewing.

[Table-of-Contents](#Table-of-Contents)

# Credits
## Content
* Text for the main section was created by myself.
* Dental products were taken from the below sites:
[Site A](https://)
[Site B](https://)

### Media
* The photos used in this website were taken from some resources such as the below.
    * Pexels.com - used for images
    * Unsplash.com - used for images
    * Google.com - used for images

### Acknowledgements
* Huge thank you to my mentor **Ronan McClelland** for his guidance throughout my project.
* Special thanks to Student Care support (**Bethany**) for assisting me on a delicate personal issue.

[Table-of-Contents](#Table-of-Contents)

## Comments
None so far - `github`

[Table-of-Contents](#Table-of-Contents)                                                              