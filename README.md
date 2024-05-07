![Badge](https://img.shields.io/badge/License-MIT-yellow.svg) ![JavaScript](https://img.shields.io/badge/JavaScript-orange) ![Node.js](https://img.shields.io/badge/Node.js-blue) ![Express.js@4.18.2](https://img.shields.io/badge/Express.js@4.18.2-purple) ![idb@8.0.0](https://img.shields.io/badge/idb@8.0.0-darkcyan)

<h1 align = "center"> PWA Text Editor </h1>

This project aims to develop a robust text editor web application designed to allow developers to create and manage notes or code snippets efficiently, with or without an internet connection. The application features a client-server architecture that initialises through simple commands and utilises technologies like webpack for bundling JavaScript files and IndexedDB for local data storage. The seamless functionality in the browser is ensured even when using next-generation JavaScript, enhancing reliability and user experience. Additionally, the application supports offline capabilities and easy desktop installation, making it an essential tool for developers seeking a dependable and accessible coding environment.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Central Grader Comments](#central-grader-comments)
- [License](#license)

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## Technologies Used

- JavaScript
- Node.js
- Express.js (version 4.19.2)
- idb (version 8.0.0)

## Screenshot

<b>Run Build Successful:</b>

![](/assets/images/success-run-build.png)

<br>

<b> Render Successful: </b>

![](/assets/images/success-render.png)

<br>

<b> Application for `manifest.json` file: </b>

![](/assets/images/manifest.png)

<br>

<b> Application for registered service worker: </b>

![](/assets/images/service-worker.png)

## Installation

The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/yukitoshi12345/PWA-Text-Editor/](https://github.com/yukitoshi12345/PWA-Text-Editor)

<br>

You can access the deployed application with the Render link: https://pwa-text-editor-tjti.onrender.com

## Central Grader Comments

Grade: 100/100

Hello Yukitoshi,

Greetings, Yukitoshi! Excellent work on the homework assignment! You have submitted the link to your GitHub repository which contains your application code, and you have submitted the link to your deployed application which loads without any 404 or Render errors. Well done! You have done very well regarding the technical acceptance criteria! You have created an object store using IndexedDB, and you have included both GET and PUT methods. Your application works without an internet connection. You have bundled your application with webpack, created a workbox service worker that caches static assets, used Babel for async/await, generated a manifest.json file using the WebpackPwaManifest plugin and your application can be installed as a progressive web application (PWA). Your content does get saved to local storage and to the jate object store when the DOM window is unfocused, and it remains there even after the application is refreshed. Impressively, you've ensured that the content is successfully retrieved and displayed in the text editor after the page has been refreshed, maintaining data persistence flawlessly.

Your repository quality was fantastic! Your repository quality was fantastic! Your repository has a unique name. It follows best practices in terms of file structure and file naming conventions. It also follows proper coding conventions in terms of indentation, class/id naming conventions, comments and overall coding structure. You have multiple descriptive commits. Your README file has a link to your deployed application. You have included a compelling description of your application in your own words, which greatly enhances the README file. Additionally, you have included a screenshot of the application itself, which effectively illustrates its functionality and user interface. These additions have significantly enriched your repository, providing a complete and engaging overview of what your application entails and how it looks when deployed.

Overall, this was a fantastic submission! In terms of the user experience, your application is intuitive and easy to navigate. In terms of the user interface style, it is very clean and polished. Your application now perfectly matches the mock-up functionality, reflecting an exact realization of the design specifications. This demonstrates your meticulous attention to detail and your ability to translate requirements into a polished and fully functional product. You have demonstrated a strong ability to build a PWA application, and you are turning out to be a strong web developer!

As always, if you require any assistance regarding this assignment, do not hesitate to reach out to instructional staff during office hours or any of our Learning Assistants. We are always happy to help. I wish you the best of luck on your coding journey, Yukitoshi.

- QP, Centralized Grading.

## License

This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/PWA-Text-Editor/blob/main/LICENSE).
