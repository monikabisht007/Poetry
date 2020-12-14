# Poetry-Program

Develop a front-end application which would help users list and browse poem based on Author with Titles

# Requirements

Download node.js with npm on your machine.

# Installation

$ npm install -g @angular/cli

$ ng new [project-name]

$ cd [project-name]

# Run Application and start development Server

Commands for Client Side rendering:

Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ 

$ ng serve

Commands for Server Side Rendering:

Node Express server listening on http://localhost:4000

$ ng add @nguniversal/express-engine

$ npm run build:ssr

$ npm run serve:ssr

# Run Tests

All unit tests are performed with jasmin and karma and can be configured in karma.conf.js. 

$ ng test

For Code Coverage

$ ng test --code-coverage

![](images/SpaceX_Testcases.PNG)

# Run Lint

Linting is the automated checking of your source code for programmatic and stylistic errors.

$ ng lint

![](images/SpaceX_LintingPassed.PNG)

# LightHouse Score for Performance, SEO , Accessibility and Best Practices

Score: 91

![](images/SpaceX_LighthouseforPerformance.PNG)

# Approach to develop this Angular Application

1. Once we serve the application then there will be root folder in which we have App Component, Module, Spec file, HTML and CSS file.

2. In app component we defined the Poem home page.

3. We created two folders for poem home page and poem display component.

4. When we load the page for the first time , We are going to show autocomplete search text box for authors and titles

5. When user select author and title from search box , then we are going to hit GET API for getting the data based on author and title of the poem

6. Created one service where we defined http call and return the data to poem home page component.

7. Once will get the data in the component then we will display the poem and also rhyme scheme in web page through Binding.

8. Used Angular Universal for server side rendering so it will be SEO friendly and initial launch programs landing page has to be server side rendered.

9. Unit testing done for the components by writing test cases.

Desktop View:
![](images/DesktopView.PNG)

# Heroku Deployment using GitHub

1. Create Repository on Github and upload files

2. Create Account on Heroku

3. Click new and then Create New App

4. Provide App name and click on Create app button

5. Choose deployment method as Github

6. Once connected to Git Hub then look for you repository

7. Click on Connect then click on Enable Automatic Deploy

8. After this click on Deploy Branch

9. Once deployed click on View and it will redirect to the link where application is deployed








