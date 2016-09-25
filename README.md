# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## Solution

In _jasmine/spec/feedreader.js_ file, there are 7 test fuctions, include:

1. RSS feeds are defined in `allFeeds` and are not empty.
2. Each feed in `allFeeds` has a defined and valid (simple RegExp) URL.
3. Each feed has a defined and non-blank name.
4. The navigation menu is hidden by default (on page load).
5. The nav. menu toggles visibility after clicking the menu icon.
6. The first feed has at least one entry.
7. The feed changes content after selecting a new feed.

## Installation
Download or clone this repo is [here](https://github.com/trunggm/frontend-nanodegree-feedreader). Go to folder and run _index.html_. No need some special orther.

## Author: [Trunggm](https://github.com/trunggm)
