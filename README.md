# 19 - Text Editor - Progressive Web Applications (PWA)

[![License: MIT](https://img.shields.io/badge/License-MIT-lightblue.svg)](https://opensource.org/licenses/MIT)

## Description
In this week's Challenge I build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

To build this text editor, I started with an existing application and implement methods for getting and storing data to an IndexedDB database. I used a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

You will deploy this full-stack application to Heroku

## Table of Contents
- [User-Story](#user-story)
- [Acceptance-Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Test](#test)
- [Questions](#questions)

## User-Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```


## Acceptance-Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation
To get the app running, simply head on over to the deployed link on Heroku.


## Usage
This app allows the user to ...

## License
This app is covered under MIT license. For details and limitations of this license please visit:
[License Link for MIT](https://opensource.org/licenses/MIT)


## Contributing
If you would like to share your feedback and/or contribute your best practices to make our code better, feel free to get in touch with us via:
  GitHub: [19-Text-Editor-PWA - link](https://github.com/dinozio-design/19-Text-Editor-PWA)<br>

## Test
We are using jest for testing the development of the functions. No test have been written for this application yet.
<br>

## Questions
If you have any questions, you can email them to me.
  email: <sam@dinozio.design><br>

### Deployed Links

<!-- 1. You can find the video walkthrough of a typical user flow of the application **here:** <br>
[13-E-Commerce-Back-End-ORM - vid 1 -  starting and seeding db + Category CRUDs](https://drive.google.com/file/d/1e2YqTp9xwSMpd87m7aM-Vn1WWebHmbXy/view)<br>
[13-E-Commerce-Back-End-ORM - vid 2 balance of CRUDs for products and tags](https://drive.google.com/file/d/1sNlSMLtALR2E1cHLw3cr7YZUAiKvK0Jh/view)<br> -->


2. You can find the URL of my GitHub repository that contains this code **here:** <br>[GitHub Repo - link](https://github.com/dinozio-design/19-Text-Editor-PWA)

### Authors Notes: 
  _This README and accompanying repo have been brought to you by:_<br>© Sam Azimi - 2023 CodeCamp Studen.<br>Confidential and Proprietary. All Rights Reserved.