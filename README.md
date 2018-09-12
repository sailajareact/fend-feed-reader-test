# Project Overview

This is RSS feed reader application. It uses the Google
Feed Reader API to grab RSS feeds as JSON object and display them.

Part of FEND already developed project given to me by Udacity, to write tests using Jasmine to test if the Javascript is working properly. 

## Dependencies
* Handlebars templating library
* Jquery

##  How to Run Appilcation

Download or clone repositrory from <a href="https://github.com/sailajareact/fend-feed-reader-test.git">here.</a>
Then open the index.html file in a browser.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

# Project Assets
* [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric).
* [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
* [course](https://www.udacity.com/course/ud549).
* [Jasmine documentation](http://jasmine.github.io).

# Implemented Tests

Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and Edit the `allFeeds` variable in **./js/app.js** 
to make the provided test fail and see how Jasmine visualizes this failure in application.

1. Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. A new test suite named `"The menu"` with tests that ensures the menu element is hidden by default. You'll have to analyze 
the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
4. Test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: 
does the menu display when clicked and does it hide when clicked again.
5. A test suite named `"Initial Entries"`with test that ensures when the `loadFeed` function is called and completes its work, 
there is at least a single `.entry` element within the `.feed` container.
6. A test suite named `"New Feed Selection"`. test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
