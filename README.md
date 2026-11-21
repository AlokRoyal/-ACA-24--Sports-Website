# MS Dhoni Tribute Website

![HTML](https://img.shields.io/badge/HTML5-pages-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-styling-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=black)

A static, multi-page tribute to Mahendra Singh Dhoni. This iteration expands the biography and achievements page with a separate career timeline.

## Features

- Home page with biography, achievements, and cricket imagery
- Separate timeline page with its own stylesheet
- Navigation between the home and timeline pages
- Small browser-side JavaScript behavior
- Local image assets; no remote data dependency

## How it works

The browser opens index.html as the entry page. Its links navigate to timeline.html. Each page is authored in HTML and styled with its corresponding CSS file. script.js is loaded for the small interactive behavior in the site. There is no framework, API, or server-side application.

## Architecture

Browser → index.html / timeline.html → page stylesheets and script.js → local images

## Start locally

1. Clone or download the repository.
2. Keep the HTML pages, CSS files, JavaScript, and JPG assets together.
3. Open index.html in a browser and use the page navigation.

No package manager or compilation is needed. A static server can be used if the browser restricts local file assets.

## Project layout

- index.html — home page and biography
- timeline.html — timeline page
- style.css — home page styling
- styletimeline.css — timeline styling
- script.js — browser-side interaction
- JPG files — background and cricket imagery

## Notes

The pages rely on the current relative asset paths. Keep exact filenames and capitalization when deploying to a case-sensitive host. No test or build scripts are configured, and the repository does not list a project license.