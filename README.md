# Mod19-PWA-Text-Editor

## Table of Contents
- [Introduction](#introduction)
- [Acceptance Criteria](#acceptance-criteria)
- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

As a developer I want to create notes or code snippets with or without an internet connection.

### Acceptance Criteria

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
    WHEN I deploy to Render
    THEN I should have proper build scripts for a webpack application 

## Getting Started


### Installation


1. Install dependencies:
```
npm install
```
2. Configure your database settings in config/connection.js.

3. Run the application:
```
npm run start

```
4. Open the localhost url to view the code:
 "http://localhost:3000"

5. To just view the product, click on the deployed link:
"https://text-editor-55z9.onrender.com"


## Usage

GITHUB link: (https://github.com/pauljsully/Mod21-MERN-Challenge-Book-Search-Engine.git)
DEPLOYED Link: (https://text-editor-55z9.onrender.com)

## License

[MIT License](https://opensource.org/licenses/MIT).
