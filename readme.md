# Personal Portfolio Webpage with CSS Grid
## Project Overview
This project for beginners covers HTML and CSS, and specifically focuses on CSS Flexbox by
creating a simple yet responsive personal portfolio webpage.

## Requirements:
- Use Visual Studio Code as your development.
- Initialize a Git repository for your project.
- Build a responsive personal portfolio webpage
  using HTML and CSS with a focus on CSS
  Flexbox.
- As you work on features, branch, commit, and 
  check in your code.
- Prefer the use of HTML semantic elements such as
  <span style="color: royalblue;">\<header></span>,
  <span style="color: royalblue;">\<footer></span>,
  <span style="color: royalblue;">\<article></span>, and
  <span style="color: royalblue;">\<section></span>.
- Any images should have alt attributes for
  accessibility.

## Design Choices
- I decided to use a fictional character for the subject and not myself.
- The structure outline is as follows:

  ```
  <html>
    <body>
      <header></header>
      <nav></nav>
      <section1></section1>
      <section2></section2>
      ...
      <sectionN></sectionN>
      <footer></footer>
    </body>
  </html>
  ```


- The main content section includes separate <span style="color: royalblue;">\<section></span> tags for each content type (About Me, Skills, Projects, Contact).
- The color schemes include:
  - Light and dark brown background colors.
  - Wheat foreground color.
  - Goldenrod hover decorations on URLs.
- The top bar with the image and name have a flex-direction of columns:
  - The nav bar is sticky.
  - The nav bar has a flex-direction of row.
  - The nav bar is responsive and will change to flex-direction column if the window size is decreased below 400px in width.
- I added this readme.md as requested to help with understanding the project.