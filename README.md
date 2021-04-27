# budget_tracker

Progressive Web Applications (PWA)

User Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
Acceptance Criteria
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
Mock-Up
The following image shows the web application's appearance and functionality:

At the top of a graph, text says, “Your total is: $455,” above options to add or subtract funds and a chart showing total over time.
Getting Started
Review the following lessons to complete this challenge.

Offline Functionality
You’ll need to use IndexedDB to add offline functionality. Review Module 18: NoSQL, Lesson 4: Add Offline Persistence with IndexedDB as a refresher on how to add this to your application.

You’ll also need to add a service worker to your application. Review Module 19: Progressive Web Applications (PWA), Lesson 4: Using Service Workers as a refresher on how to add this to your application.

REWIND
The Food Festival application that you created in this module's lessons did not include an Express.js server, so you used the webpack-dev-server npm module to test the service worker with an HTTPS-enabled server.

For this Challenge, however, you aren't using webpack, but you do have an Express.js server provided to you in the starter code. Remember that Chrome DevTools makes it possible to test service workers on localhost in development. Simply click the Application tab, then select Service Workers from the menu on the left.

IMPORTANT
You should add your idb.js file to the public/js/ directory of your application.

You should add your service worker to the root of the public/ directory of your application.

Once you’ve updated the existing budget tracker, it should provide the following functionality:

The ability to enter deposits offline.

The ability to enter expenses offline.

Offline entries should be added to the tracker when the application is brought back online.

Web Manifest
Because this will be a mobile-first application, you’ll also need to add a web manifest to your application with the app’s metadata, to let users’ devices know what they’re installing and how the app should look on the home screen.

This manifest.json file for this project will contain the following properties:

name

short_name

icons

theme_color

background_color

start_url

display

IMPORTANT
In the module project, you used webpack to create the manifest.json file. For this application, you’ll need to create it manually and add it to the root of the public/ directory of your application. You can also review Module 19: Progressive Web Applications (PWA), Lesson 5: Convert the App to a PWA as a refresher on web manifests.

Deployment to Heroku Using MongoDB Atlas
Finally, the budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas. To review this process, look at Module 18: NoSQL, Lesson 5: Add Mongoose Validation, specifically 18.5.5: Deploy to Heroku.

Grading Requirements
This Challenge is graded based on the following criteria:

Technical Acceptance Criteria: 40%
Satisfies all of the preceding acceptance criteria plus the following:

Application must include a service worker.

Application must include a web manifest.

Application must use IndexedDB for offline functionality.

Application must be deployed to Heroku.

Deployment: 32%
Application deployed at live URL.

Application loads with no errors.

Application GitHub URL submitted.

GitHub repository contains application code.

Application Quality: 15%
User experience is intuitive and easy to navigate.
Repository Quality: 13%
Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains high-quality README file with description, screenshot, and link to deployed application.

How to Submit the Challenge
You are required to submit BOTH of the following for review:

The URL of the functional, deployed application.

The URL of the GitHub repository, with a unique name and a README describing the project.

NOTE
You are allowed to miss up to two Challenge assignments and still earn your certificate. If you complete all Challenge assignments, your lowest two grades will be dropped. If you wish to skip this assignment, click Submit, then indicate that you are skipping by typing “I choose to skip this assignment” in the text box.

© 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
Submission
Not Submitted!
Submission Details
Grade: 0 (100 pts possible)
Graded Anonymously: no
Comments:
This is a placeholder for your unsubmitted assignment! Please reach out to staff if you have any questions or concerns. -Central Grader Angel
Grader Coding, Apr 20 at 1:03pm
