# YourFIT

YourFIT is a fitness application that invites the user to take control of their health and wellbeing to be the best possible version of themselves. The aim is to set up each user with some form of fitness and nutrition plan via purchasing a once off product available on the site or a subscription service where the user is provided a new plan each week. 
No fitness journey is complete without a proper outfit to take on the world in. That is why YourFIT also provides some clothing options and bundle deals so users who are new to exercise can get themselves kitted out. This way when leavivng the website the new user has both a plan and activewear to begin their new journey. 


# UX

## How To Navigate
To ensure the navigation process is as simple as possible the user is greeted with one block of text on the home page. It oulines that they need to register to create their recipes. The add recipes section is also hidden until the registration process has been completed to ensure no confusion is experienced when first viewing the website.

Everything else is displayed as a form, something universal to all users to ensure that people aren't confused. Additional button features are kept to a minimum so virtually anyone can navigate the website.

## Clicks To Create
The nav bar at the top of each page ensures that there are a limited amount of clicks on each page to get the user to start create and checking out recipes as soon as possible. 

Once the user is registered they can get straight to the add recipes section in one click as it is located in the nav bar once they are set up.

## User Ambitions
The user group for Find Cuisine is anyone with basic computer skills simply looking to find and share recipes in order to: 

* try something new in the lines of nutrition, exercise or both
* buy new activewear clothing in a size that fits them
* navigate a simple user interface to find the product they are after
* be apart of a something bigger than themselves
* here success stories on others goals and achievements since joining the website
* reorganise products in order to find them based on certain criteria such as pricing or rating etc
* track your spending as you go about the website

These ambitions are achieved through YourFIT by: 

* Having programmes available to purchase that contain nutrition and exercise plans
* Having several items of clothing on the site available to purchase with multiple sizing options
* Featuring a simplistic navigation bar on both desktop and mobile with a very clear layout for users to navigate with ease
* Being able to create an account to mark how you are apart of the YourFIT community
* Read different success stories and reviews from previous users of programmes on the site
* Find the best options and products to buy and being able to rearrange the listing to display the best objects first
* providing a shopping cart feature in the top right of the screen displaying the sum total of all of your purchases

## User Stories

As a general user who is looking to get into a new fitness/nutrition programme, I want to:

 * See all available products for purchase and pay using Stripe
 * Have quick access to my purchased goods in terms of 
 * Have reassuring messages flashed on screen to ensure I am doing the right thing on the website
 * Create my own recipes
 * Navigate the website without fear of being confused
 * Have the ability to edit / delete recipes in case I make a mistake or want to take my recipe down 


# Apps and Features

## Apps

## Shopping Cart
Upon clicking on to the website the user can register their soon to be log in details and create their own unique username which is then stored on a database with a hash security protection on their password in order to protect their details. 

No two users can have the same username making sure that each user is unique on the website.

## Account Set
Once registered the user can come back to the web page time and time again and log back in using their registered details. The database indefinitely stores username and password meaning a user can come back at any time and access their recipes and continue on creating them for years to come. 

## Products
Users can create their own recipes via the Add Recipe page. Different sections of the form ensure that the user must enter details into a given section of the form to make sure no false/half empty recipes are flooded on to the website

## Features

## Review Section
The recipes page contains all newly created recipes and dispays them all on to one page for users to see. Each user is responsible for editing and deleting recipes and won't be able to effect anyone elses recipes bar their own. 

## Navigation bar + Search bar
In the image link section of the the Add Recipe form the user can input an image link of their meal and will have it displayed on top of their recipe. This creates both a personal element and aids with visual information as to what exactly a user should expect the meal to look like.  

## Product Reorganisation

# Colour Scheme 

## Black and White Theme
Upon researching for the general fitness / healthy living vibe some very distinct colour patterns came through. For me what appealed most was a black and white theme with pictures providing other color dynamics.

* Black
* White
* Light & Dark variations of grey for general content which can be seen on the main index page

# Features Left To Implement

## Emailing service for subscriptions

As it stands the users profile page is a rather blank html page that simply displays the users username. 

Given more time I would add it in that on the users profile page their is a section that displays the users recipes and not anyone elses. Currently the user will have to sive through all the other recipes to check on their own. 

## Community chat page

Having a page where members of the YourFIT website can display their progress/ thoughts and opionions on a timeline to improve on the community aspect to the app



# Technologies Used

 * HTML, CSS and JQuery were the programming languages used in the coding of this project.
 * For scaling Bootstrap CDN was used to add a more responsive website
 * Django has been incorporated to handle all of the backend for the project
 * Gitpod used to deploy the project alongside Heroku
 * materialise has been used for certain grid layouts and sidebars on the mobile version
 * Font Awesome used for icons displayed throughout the website pages
 * Pillow is being used for processing images on the website products

# Mock Up Designs

## General structure to website and rescaling on a mobile device

In the link below you will be brought to a folder consisting of two images. One shows the general outline of a rough design to how I want the website to look.

The other is of how I want the mobile version to work taking inspiration from a previous project. It shows a demonstration of how I want the navbar to expand out when clicked. 

https://drive.google.com/drive/folders/1PNapI7VY0qElQZmbSVo3I-s-yhwpEVPF?usp=sharing 

 
# Testing 

### As a general user who plays games on the internet, See where my created recipes go

All newly created recipes by any users are all added to the recipes page where it acts as a directory where anyone can search for their recipes and other users recipes that they have created on the website.

### As a general user I want to have reassuring messages flashed on screen to ensure I am doing the right thing on the website

As the user registers, logs in and adds recipes to website they are flashed reassuring messages to say that they have completed that step successfully provided all details entered in are correct. 

### As a general user I want to create my own recipes

This can be completed via the add recipes page. Once the user has entered all their details and submitted an image link they can simply click on the Add Recipe button and instantly their recipe gets added to the recipe page to be viewed by all.

### As a general user I want to have the ability to edit / delete recipes in case I make a mistake or want to take my recipe down

The user can simply click on the recipes page and have two very clear buttons displayed on their recipe where they can choose to either edit or delete. 

On clicking delete the recipe will be wiped from the database and no longer be available. 

On clicking edit the user is taken to an edit recipe page where they can edit recipes where the recipe details will be displayed ready for them to edit and change. 

### As a general user I want to navigate the website without fear of being confused

The layout of the website was made specifically so there are a minimal amount of clicks to navigate with a minimal amount of buttons to click to progress through a given task.

# Validators

### W3C HTML Validation Service

No major issues detected. 

### W3C CSS Validator Service
No major issues detected. Validator did not understand certain colours selected. These error messages can be ignored. 

# Known issues
When the user edits a recipe it comes up as a new recipe and they are forced to manually delete their original one.

Odd popout feature occurs for a split second when a recipe is deleted.

# Version Control

## Gitpod 
Gitpod was chosen for the version control of the project from the very beginning. 

## GitHub

GitHub was used as a repository for everything pushed from Gitpod.

# Deployment

## Gitpod 

The entire project has been coded on Gitpod starting from the first commit. It allows for the sharing of running workspaces making tutor/mentor sessions run smoother.

In order to commit and push to GitHub:

    git add .
    git commit -m "Insert commit Message Here"
    git push 

After each main section of the project was completed a commit and push was used to ensure proper tracking and proper commit etiquette was used throughout. This also prevents the entire project being lossed due to unforeseen circumstances such as server crashes / late night server updates.

GitHub Pages was used to deploy the site. Upon selecting a name for the project, "Settings" was selected. Then proceeded to the "GitHub Pages" section where the "Source" was switched to "Master branch". At the top of the page a link is then found to the deployed website where it is submitted during the project submission section for grading.

## Heroku 

To deploy my project to Heroku the following steps were followed:

* Go to the "settings" page in heroku app
* To set up heroku config vars from Gitpod to Heroku, scroll down  and click on "Reveal Config Vars" section:
* Type in "IP" to KEY and "0.0.0.0" to value 
* Type in "PORT" to KEY and "5000" to value 
* Type in "MONGO_URI" to KEY and "mongodb+srv://joeDoyler:<password>@myfirstcluster-y6kfn.mongodb.net/recipe_database?retryWrites=true&w=majority" to value 
* Type in "SECRET_KEY" to KEY and "<secret_key>" to value 


# Hosting

## Heroku 

Heroku has been chosen to host the app for this project.



# GitHub repository link




# Credits 

## Content & Acknowledgements

A massive influence for this project came directly from the course content available to students. The Ecommerce Boutique Ado project had many logical similarities to fulfilling some of the needs of the project itself with some features missing from it such as the review section and setting up the exercise and nutrition plans. 

The styling for the index page is influenced by both the course material and https://www.youtube.com/watch?v=KmlMXUxL-nM&t=687s video on creating a gym website. I found the frontend to be quite visually. This method of picture on left and content on the right is replicated in the programme section. 

Furthermore, on several issues interacted with on the project a massive support was drawn from the mentors helping on previous projects as I had no access to tutor support while doing this project.

## Media 

All images were found on https://www.pexels.com/ and from a https://www.kaggle.com/ database provided through the course material. All images provided are copyright free and readily available on the sites for anyone to use. 

