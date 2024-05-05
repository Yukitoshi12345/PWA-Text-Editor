<h1 align = "center"> PWA Text Editor </h1>

This project aims to develop a robust text editor web application designed to allow developers to create and manage notes or code snippets efficiently, with or without an internet connection. The application features a client-server architecture that initializes through simple commands and utilizes technologies like webpack for bundling JavaScript files and IndexedDB for local data storage. The seamless functionality in the browser is ensured even when using next-generation JavaScript, enhancing reliability and user experience. Additionally, the application supports offline capabilities and easy desktop installation, making it an essential tool for developers seeking a dependable and accessible coding environment.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
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

## Screenshot

<b>Run Build Successful:</b>

![](/assets/images/sucess-run-build.png)

<br>

<b>Render Successful:</b>

![](/assets/images/success-render.png)

<br>

## Installation

The project was uploaded to [GitHub](https://github.com/) at the following repository:
[https://github.com/yukitoshi12345/PWA-Text-Editor/](https://github.com/yukitoshi12345/PWA-Text-Editor)

<br>

You can access the deployed application with the Render link: https://pwa-text-editor-tjti.onrender.com

## License

This project is licensed under the [MIT License](https://github.com/Yukitoshi12345/PWA-Text-Editor/blob/main/LICENSE).
