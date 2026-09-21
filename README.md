# HTML & CSS Design Three

A responsive front-end implementation of an educational web design by **Osama Elzero / Elzero Web School**, built from scratch using HTML5 and CSS3 as part of my front-end development learning journey.

This is my **third complete HTML & CSS project**. While the original design was provided as a learning reference, I implemented the page independently and introduced my own layout decisions, CSS effects, animations, responsive improvements, and fixes for issues encountered during development.

## Live Demo

[View Live Demo](https://YHS003.github.io/HTML_CSS_Design_Three/)

> The project is deployed using GitHub Pages.

## Screenshots

Screenshots of the implemented project are included below to demonstrate the responsive layout, custom interactions, and visual result across different screen sizes.

<table>
  <tr>
    <td align="center" valign="top">
      <strong>Desktop — Full Page</strong><br><br>
      <img src="screenshots/Full-Desktop.png" alt="Desktop Full Page" width="450">
    </td>
    <td align="center" valign="top">
      <strong>Mobile — Full Page</strong><br><br>
      <img src="screenshots/Full-Mobile.png" alt="Mobile Full Page" width="300">
    </td>
  </tr>
  <tr>
    <td align="center" valign="top">
      <strong>Desktop — Header & Landing</strong><br><br>
      <img src="screenshots/Desktop_Header_Landing.png" alt="Desktop Header and Landing" width="450">
    </td>
    <td align="center" valign="top">
      <strong>Desktop — Mega Menu</strong><br><br>
      <img src="screenshots/Mega-Menu-Desktop.png" alt="Desktop Mega Menu" width="450">
    </td>
  </tr>
  <tr>
    <td align="center" valign="top">
      <strong>Mobile — Selected Section</strong><br><br>
      <img src="screenshots/Section-Mobile.jpg" alt="Mobile Selected Section" width="300">
    </td>
    <td align="center" valign="top">
      <strong>Desktop — Footer</strong><br><br>
      <img src="screenshots/Footer-Desktop.png" alt="Desktop Footer" width="450">
    </td>
  </tr>
</table>

## About the Project

This project was developed while studying front-end development through the **Elzero Web School** course.

The original design was provided as part of the course for learning and practice. Rather than simply reproducing the tutorial implementation, I used the design as a reference and built the page while making my own decisions about layout, styling, animations, interactions, and responsive behavior.

During the implementation, I also encountered several layout and responsive issues and solved them through additional CSS adjustments and experimentation.

The page contains multiple sections, including:

* Articles
* Gallery
* Features
* Testimonials
* Team Members
* Services
* Skills
* Work Steps
* Events
* Pricing Plans
* Videos
* Statistics
* Discount
* Subscribe
* Footer

## What I Added

Although the project is based on an educational design provided by **Osama Elzero**, the implementation includes several custom layout decisions, CSS interactions, animations, responsive improvements, and fixes that I developed independently during the implementation.

### Articles

* Added a custom `transform` effect to the article cards that was not included in the original implementation.
* Solved several layout and positioning issues that appeared while implementing the effect and integrating it with the responsive layout.

### Features

* Fixed the responsive triangle animation in the Features section.
* Adjusted the triangle at the `991px` breakpoint where the original responsive behavior caused the shape to become incomplete.
* Refined the responsive behavior to keep the visual effect consistent across screen sizes.

### Testimonials

* Added custom CSS effects and interactions to the testimonial cards.
* Designed the visual behavior independently rather than reproducing the original static presentation.

### Team Members

* Customized the social media icons and their hover behavior.
* Added custom hover effects with background transitions and icon color changes.
* Designed the interaction to provide a more polished and modern visual effect.

### Images & Animations

The original design uses animated imagery in the landing section while most other section images remain static.

I extended this concept by applying similar image animation effects to images across multiple sections of the page, while keeping the animations responsive and visually consistent.

### Skills

* Customized the skill progress bars with an additional hover interaction.
* The progress bars initially display their actual percentage.
* When hovering over a progress bar, it resets to zero and then animates back to its original percentage.

This creates an additional visual interaction while keeping the original percentage information visible.

### Subscribe Section

The original mobile layout places the email field and submit button vertically.

I modified the responsive layout to preserve the desktop-style horizontal form structure on smaller screens.

This required additional responsive sizing and Flexbox adjustments to prevent overflow and maintain the correct proportions and spacing on mobile devices.

### Responsive Images

The original implementation hides many section images on smaller screens.

Instead of removing them on mobile, I kept the images visible and redesigned their responsive behavior so they could remain part of the layout without breaking the page structure.

This required additional adjustments to:

* Image sizing
* Positioning
* Spacing
* Section layout
* Responsive breakpoints

### Footer

* Added a **back-to-top button** that allows the user to quickly return to the top of the page.
* Added custom `transform` effects to the footer images.
* Added additional hover behavior to make the footer elements more interactive.

### General Responsive Improvements

Throughout the project, I made additional responsive adjustments beyond the original implementation.

These included:

* Fixing layout issues at specific breakpoints.
* Adjusting elements that caused overflow or incomplete visual effects.
* Keeping visual elements that were originally hidden on mobile.
* Reworking layouts where necessary to preserve the desktop design on smaller screens.
* Testing and refining the page across different viewport sizes.

## Technologies Used

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Media Queries
* CSS Transitions
* CSS Animations
* CSS `transform`
* CSS Pseudo-elements
* Font Awesome
* Normalize.css
* Google Fonts

## JavaScript

**JavaScript is not used in this version of the project.**

The project was built using HTML and CSS only, as JavaScript had not yet been introduced at this stage of my learning journey.

The interactions and visual behaviors in this version are therefore implemented using CSS hover states, transitions, transforms, and animations.

The project may be revisited after learning JavaScript to replace CSS-based visual simulations with fully functional JavaScript interactions where appropriate.

## Responsive Design

The page was implemented with responsive layouts for different screen sizes, including desktop, tablet, and mobile views.

Media queries were used to adjust:

* Navigation and mega menu layout
* Grid structures
* Section spacing
* Typography
* Images
* Cards
* Progress bars
* Pricing plans
* Content positioning
* Overall page layout

Additional responsive work was also performed to preserve elements that were originally hidden on mobile and to fix visual issues at specific breakpoints.

## Project Structure

```text
HTML_CSS_Design_Three/
│
├── index.html
│
├── css/
│   ├── normalize.css
│   ├── all.min.css
│   └── master.css
│
├── assets/
│   ├── avatar-01.png
│   ├── avatar-02.png
│   ├── avatar-03.png
│   ├── avatar-04.png
│   ├── avatar-05.png
│   ├── avatar-06.png
│   ├── cat-01.jpg
│   ├── cat-02.jpg
│   ├── cat-03.jpg
│   ├── cat-04.jpg
│   ├── cat-05.jpg
│   ├── cat-06.jpg
│   ├── cat-07.jpg
│   ├── cat-08.jpg
│   ├── discount-background1.jpg
│   ├── discount-background2.jpg
│   ├── discount.png
│   ├── discount2.png
│   ├── events.png
│   ├── features-01.jpg
│   ├── features-02.jpg
│   ├── features-03.jpg
│   ├── gallery-01.png
│   ├── gallery-02.png
│   ├── gallery-03.jpg
│   ├── gallery-04.png
│   ├── gallery-05.jpg
│   ├── gallery-06.jpg
│   ├── hosting-advanced.png
│   ├── hosting-basic.png
│   ├── hosting-professional.png
│   ├── landing-image.png
│   ├── landing.jpg
│   ├── megamenu.png
│   ├── skills.png
│   ├── stats.jpg
│   ├── team-01.jpg
│   ├── team-02.jpg
│   ├── team-03.jpg
│   ├── team-04.jpg
│   ├── team-05.png
│   ├── team-06.jpg
│   ├── team-07.jpg
│   ├── team-08.jpg
│   ├── video-preview.jpg
│   ├── videos-01.jpg
│   ├── work-steps-1.png
│   ├── work-steps-2.png
│   ├── work-steps-3.png
│   └── work-steps.png
│
├── webfonts/
│   ├── fa-brands-400.woff2
│   ├── fa-regular-400.woff2
│   ├── fa-solid-900.woff2
│   └── fa-v4compatibility.woff2
│
├── screenshots/
│   ├── Desktop_Header_Landing.png
│   ├── Footer-Desktop.png
│   ├── Full-Desktop.png
│   ├── Full-Mobile.png
│   ├── Mega-Menu-Desktop.png
│   └── Section-Mobile.jpg
│
├── .gitignore
├── LICENSE
└── README.md
```

## Learning Context

This project is the **third complete HTML & CSS design** I have implemented during my front-end development learning journey.

Compared with my earlier projects, this project gave me more experience working with a larger stylesheet and a page containing many different sections, layouts, animations, and responsive behaviors.

It helped me improve my ability to:

* Translate a visual design into HTML structure.
* Choose between CSS Grid and Flexbox depending on the layout.
* Build responsive layouts from scratch.
* Modify existing HTML structures when needed.
* Create custom CSS interactions and animations.
* Use pseudo-elements for visual effects.
* Debug responsive and layout issues.
* Handle images and complex layouts across different screen sizes.
* Make independent implementation decisions instead of relying entirely on the tutorial solution.

## Design Credit

The original visual design and educational material are provided by:

**Osama Elzero / Elzero Web School**

The design is used as part of the Elzero Web School course for learning and practice.

The original design, branding, images, and other third-party assets are not claimed as my own.

This repository contains my own HTML/CSS implementation, modifications, responsive improvements, and custom CSS effects based on that educational design.

## Credits

### Original Design & Learning Resource

**Osama Elzero / Elzero Web School**

The project was implemented as part of the front-end development learning material provided by Elzero Web School.

### Assets

The project uses images, icons, fonts, and other assets associated with the educational design.

The ownership and copyright of third-party assets remain with their respective owners.

## Clone the Repository

If you have access to the repository, you can clone it using:

```bash
git clone https://github.com/YHS003/HTML_CSS_Design_Three.git
```

Then navigate to the project directory:

```bash
cd HTML_CSS_Design_Three
```

The project can be opened directly in a browser or run using a local development server such as **Live Server** in VS Code.

> **Note:** The repository is currently private, so GitHub access is required to clone it.

## Author

**Yehya Hamdy Shehata**

GitHub: [@YHS003](https://github.com/YHS003)

## License

This repository is published primarily as a **portfolio and educational project**.

The HTML/CSS implementation written by me may be used, studied, modified, and adapted for personal learning and portfolio purposes, subject to the terms of the [`LICENSE`](LICENSE) file.

The original design, images, fonts, icons, and other third-party assets remain subject to their respective owners' copyrights and licenses.

Please refer to the [`LICENSE`](LICENSE) file for the complete terms.