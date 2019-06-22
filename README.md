# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## What will I learn?

You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

## How will this help my career?

Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.

Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

# Development Strategy

For a refresher (or reference) before you begin writing code, we recommend reviewing the content from [JavaScript Testing](https://www.udacity.com/course/javascript-testing--ud549). Your project will be evaluated by a Udacity code reviewer according to the [Feed Reader Testing project rubric](https://review.udacity.com/#!/rubrics/18/view). Please review for detailed project requirements.

1.  Familiarize yourself with the starter code
    -   Open up `index.html` and review the functionality of the application within your browser
    -   What is all the code in `app.js` doing? Be sure to read all code comments
    -   Check out `style.css`. How is styling applied to the application?
2.  Explore the Jasmine spec file in `feedreader.js`
    -   This is the file in which you'll be writing your tests
    -   Make sure to read all code comments here as well
    -   Review the [Jasmine documentation](http://jasmine.github.io) if needed
3.  Edit the `allFeeds` variable in `app.js` to make the provided test fail
    -   See how Jasmine visualizes this failure in your application
    -   Return the `allFeeds` variable to a passing state after reviewing the failed test
4.  Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined _and_ that the URL is not empty
    -   For example, how would you use a `for...of` loop in this test?
5.  Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty
    -   Think about how you wrote the previous test. What are you testing for this time?
6.  Write a new test suite named `"The menu"`
    -   What are you `describe`-ing in this test suite?
7.  Write a test that ensures the menu element is hidden by default
    -   You'll have to analyze the HTML and the CSS to determine how the hiding/showing of the menu element is implemented
    -   What code in `app.js` is directly involved with toggling the menu on and off?
8.  Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display itself when clicked, and does it hide when clicked again?
    -   Think about how you wrote the previous test. What is different this time around?
    -   Which clickable element are you checking for?
    -   How do you "simulate" a mouse click that element without actually clicking it?
9.  Write a test suite named `"Initial Entries"`
    -   What are you `describe`-ing in this test suite?
10. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container
    -   How does Jasmine's `beforeEach()`function work?
    -   How does the `loadFeed()` function in `app.js` work? Is it synchronous or asynchronous?
11. Write a test suite named `"New Feed Selection"`
    -   What are you `describe`-ing in this test suite?
12. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes
    -   How is this test different from the previous test?

Additionally, note that:

-   No test should be dependent on the results of another
-   Callbacks should be used to ensure that feeds are loaded before they are tested
-   Error handling should be implemented for undefined variables and out-of-bound array access
-   When complete, all of your tests should pass

When you're all finished, write a `README` file detailing all steps required to successfully run the application. If you have added additional tests, provide documentation for what these future features are and what the tests are checking for.

# Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

### cloning and downloading the project

1.  I had gone throughall the instructions which were given by `UDACITY` in the rubic structure from the link `https://github.com/udacity/frontend-nanodegree-feedreader`.
2.  I have downloaded the zip folder and I extracted the zip folder from unzipped folder.
3.  After cloning I had refreshed through all the files which were provided by them such as:
    `index.html`
    `style.css`
    `app.js`
4.  I also referred the jasmine framework file `feedreader.js` to know which steps I need to resolve the issues by referring the links provided by `UDACITY`.

### Opening the project

1.  I have downloaded the zip file from the repository of GITHUB URL given in the project rubrics.
2.  After that  i have opened a terminal and changed directory to my Project folder.
3.  I installed a google chrome web server extension and opened the project folder through
    the extension  ,even we can directly run the program but we can't check the accessibility,
    audits and performance without server.

### Jasmine framework

1.  I went through the `feedreader.js` and I understood what have to be done.
2.  I've gone through all the framework and understood what changes had to be done for test suites in `feedreader.js`.
3.  I learnt methods in jasmine framework methods and functions to conduct the tests.

### Test suites

1.  In the beginning I wrote test suite for checking the test cases on `feedreader.js`.
2.  I had changed the content in `app.js` file to solve the `allFeeds` test.
3.  I had also written the first case for `URL` fields `All feeds defined and not empty` and observed `allFeeds[]` array from `app.js`.
4.  I also resolved cases such as `menu-hidden`, to test that `menu is initially hidden`, while click on menu icon visibility of menu gets true and appears.
5.  After that the written test case that checking the entries not to be zero after loading.
6.  To verify intial entries are differ from final entries I've followed the two functions:
    `Load Feed(0,function())` function loads the intial entries for finding.
    `Load Feed(1,function())` function loads the new entries for finding.
7.  I ensured that there will be no result to be depended on the other.
8.  call backs should be used to ensure that feeds are loaded before they are tested.
9.  Make sure you are connected to a good internet.
10. I had verified all test pass.

### My assumptions and knowledge after completion of project

1.  I gained some knowledge while completing the project in the field of jasmine framework.
2.  It will be my one of best project where I've explored my own ideas and own thinking capacity.
3.  Really `UDACITY` team provides good oppurtinity for students to explore their skills and abilities to develop projects which in turn will be useful in their future projects or something else
