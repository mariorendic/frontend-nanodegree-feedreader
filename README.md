## Feed Reader Testing
* This is a project to test a feedReader code in Jasmine.js with jQuery to select DOM elements.

## How to run test locally
* Download this zip file to your Computer from: https://github.com/mariorendic/frontend-nanodegree-feedreader
* Or Clone repo from github: $ git clone https://github.com/mariorendic/frontend-nanodegree-feedreader.git
* Open index.html, you should be able to see the feeds load.

## Tests implemented
* Tests to make sure that the allFeeds variable has been defined and that it is not empty.
* Loops through each feed and determines if the URL is defined and not empty.
* Loops through each feed and determines that each feed has a name and not empty.
* Ensures the menu element is hidden by default.
* Validates proper functioning of the hamburger menu toggle.
* Tests that there is at least one entry in feed.
* Tests that new content is loaded by loadFeed().

## Technologies
* Jasmine
* jQuery
* HTML/CSS