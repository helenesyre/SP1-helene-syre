# (FM1AIS175) SP1 - Semester Project 1

The Community Science Museum is a fun and interactive museum opening in your local area. It is designed for children aged 7–15 and their families, with exciting exhibits that make learning about science enjoyable and engaging.

---

## Table of Contents

- [Project overview](#project-overview)
- [Brief](#brief)
- [Features](#features)
- [WAVE Web Accessibility Tools](#wave-web-accessibility-tools)
- [Markup Validation Service](#markup-validation-service)
- [Github Jekyll](#github-jekyll)
- [Contact](#contact)

---

## Project overview

This website is made with HTML and CSS.

Link to Sketches: https://www.figma.com/proto/AzFvqG5O64SvHSaFR40bTA/-FM1AIS175--SP1---Semester-Project-1?page-id=1%3A10&node-id=1-2138&viewport=-10864%2C-1117%2C2.42&t=QVjcMRtmq569rXT2-1&scaling=scale-down-width&content-scaling=fixed&starting-point-node-id=1%3A2138&show-proto-sidebar=1

Link to Website: https://helenesyre.github.io/SP1-helene-syre/index.html

Link to the GitHub repository: https://github.com/helenesyre/SP1-helene-syre

Link to project planning board: https://github.com/users/helenesyre/projects/8/views/1

> If you have trouble opening the Figma Prototype, try opening it in a different browser.

## Brief

An interactive science museum called the Community Science Museum is opening in your town/city. Its core target audience is primary and middle school children (ages 7-15) and families with young children.

The website should be informative and engaging, encouraging viewers to visit the museum. It should also be responsive and easy to use on various devices. Peer/Teacher review is recommended.

You have been provided with assets such as text and images (see link under Resources). You must decide how these will be used in terms of presentation, hierarchy, and design. If any assets are too large, remember to optimize file sizes to ensure smooth loading and a polished user experience.

You have the choice to work on this individually or as part of a team of two.

---

## Features

- `Responsive Design` - Fully responsive layout that adapts to mobile, tablet, and desktop screens.
- `Interactive Homepage` - Engaging sections highlighting exhibitions, events, and visitor information.
- `Exhibition Pages` - Detailed pages for each exhibit with descriptions and supporting imagery.
- `Contact & Visit Info` – Clear and accessible information on how to visit, including contact form and map.
- `Accessible & Semantic HTML` – Built with accessibility and clean semantic markup in mind.
- `Modern Styling` – Styled with CSS, focusing on readability and user-friendly interface.

---

## WAVE Web Accessibility Tools

When I was checking accessibility at WAVE, there weren't too many changes that needed to be fixed. Here were the biggest issues, the same id on the clipPath from the SVG files. These were all `<clipPath id="clippath">`, where I then changed them to have numbers behind them where needed.

Otherwise, I also had problems with "empty link" in the navigation, where this applied to the hamburger and close icon, and the search icon. I fixed these by adding `<span>` with a class called `sr-only`, with some help from my teacher and [WebAIM](https://webaim.org/techniques/css/invisiblecontent/). Other than that, I changed some headings because it skipped a heading on some pages.

## Markup Validation Service

The most I had to change in the validator test was self-closing html lines and "missing headings" that were accidentally inserted into too many sections. I chose to ignore a few of the warnings for this as it was either just an image or other reasons that didn't need to be changed. [Maps.ie](https://www.maps.ie/create-google-map/) had a great page for copying and pasting an iframe to get a responsive Google Maps. This worked until it was time to validate and more errors than Figure 10 showed. I then found a new solution at [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/iframe) that worked much better and was up to date.

## Github Jekyll

Like last time I added a .nojekyll file to the root of my project since [The Github Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll). processing was blocking files like \_reset.css and \_variables.css because of the underscores. This disabled the processing, and the files could load like they should with no more issues.

## Contact

Created by [Helene Syre](https://syre-design.webflow.io/)  
Feel free to reach out: syrehelene@gmail.com
