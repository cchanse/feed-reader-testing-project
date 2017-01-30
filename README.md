# Feed Reader Testing Project

## About
Develop test suites using [Jasmine](http://jasmine.github.io/) for a web-based application that reads RSS feeds. Tests include:

* a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
* a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
* a new test suite named `"The menu"`.
* a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
* a test suite named `"Initial Entries"`.
* a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
* a test suite named `"New Feed Selection"`.
* a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.


## How to Run tests
Download all files (maintaining current folder and file structure) and open up index.html in a browser. You should then click on the menu and select another feed in order to run all tests. At the bottom of the page, you'll see Jasmine test results.
