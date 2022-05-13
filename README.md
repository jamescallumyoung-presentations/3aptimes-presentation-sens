# 3apedia2022-presentation-axa-pods-npm

> My presentation for 3apedia 2022 on Microfrontends and Axa's Pod implementation.

## 3apedia

3apedia is an internal conference and workshop we run at [3AP](https://3ap.ch).
Each year, we get together and present to one another the topics, technology, and cool things we've been working on.

## reveal.js

This presentation is created with [reveal.js](https://revealjs.com), a JS-based presentation tool.
reveal.js takes regular HTML, annotated with their classes and attributes, and creates a slick animated presentation that can be shown from a browser.
reveal.js can also parse Markdown. I've used both HTML and Markdown for this presentation.

## Running the presentation

Simply start a web server, and serve the `index.html` page.
There's a server provided in the dependencies so you can just run `npm run start`, and navigate to `http://localhost:3000/src/`, to get started quickly.

There is no build process required; just change the HTML and you're good to go.

## PDF Export

You can create a PDF version of the presentation by going to `https://localhost:3000/src/?print-pdf` and printing the page.
Remember to set the printout to landscape and set Margins to "none". If you want to include the backgrounds, enable "Print backgrounds" too.
