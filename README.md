# Manage Landing Page

This is a responsive landing page for a productivity tool called Manage. The page is designed to showcase the features, testimonials, and benefits of using Manage for team collaboration and productivity. It is built using HTML, CSS, and Bootstrap for responsiveness and styling.

## Table of contents

- [Features](#Features)
  - [Technologies Used](#Technologies-Used)
  - [Usage](#Usage)
  - [Links](#links)
- [Responsive Design](#Responsive-Design)
  - [Meta Tags and SEO](#Meta-Tags-and-SEO)
  - [JavaScript Functionality](#JavaScript-Functionality)
  - [License](#License)

## Features

Responsive Design: The page is fully responsive and works seamlessly on all devices (desktop, tablet, and mobile).
Bootstrap Integration: Utilizes Bootstrap for layout, grid system, and components like the navbar, cards, and carousel.
Testimonial Carousel: Displays user testimonials in a carousel format for large screens and a single-card view for smaller screens.
Email Validation: Includes a simple email validation feature using JavaScript.
SEO Optimization: Includes meta tags for search engine optimization (SEO) and social media sharing.

## Technologies Used

HTML5: For structuring the content.
CSS3: For styling the page.
Bootstrap 5: For responsive design and pre-built components.
JavaScript: For email validation and interactive elements.
Google Fonts: Uses the "Be Vietnam Pro" font for typography.
Bootstrap Icons: For icons used in the navbar and other sections.

## Usage

Navbar: The navbar is responsive and collapses into a hamburger menu on smaller screens.
Header Section: Displays a hero image and a call-to-action button.
Features Section: Highlights the key features of Manage with numbered cards.
Testimonials Section: Shows user testimonials in a carousel for large screens and a single-card view for smaller screens.
Pre-Footer Section: A call-to-action section encouraging users to get started.
Footer: Contains links, social media icons, and an email subscription form.

## Responsive Design

The page is designed to be fully responsive:

Navbar: Collapses into a hamburger menu on smaller screens.
Header: Adjusts the layout for different screen sizes, stacking content vertically on mobile devices.
Testimonials: Uses a carousel for large screens and a single-card view for smaller screens.
Footer: Adjusts the layout and alignment for different screen sizes.

## Meta Tags and SEO

The page includes meta tags for SEO and social media sharing:

Title: "Manage Landing Page | Simplify Team Collaboration & Productivity"
Description: "Manage is a powerful tool for modern teams to collaborate, track progress, and achieve goals efficiently."
Keywords: "Manage, team collaboration, productivity tool, task management, project tracking, team goals, workflow optimization"
Open Graph Tags: For social media sharing (Facebook, Twitter, etc.).
Canonical URL: Ensures proper indexing by search engines.

## JavaScript Functionality

Email Validation: Validates the email input in the footer subscription form. Displays a warning message if the email is invalid.

    const email = document.getElementById("email");
    const warning = document.querySelector(".warning");

    email.addEventListener("input", function () {
      const emailValue = email.value;
      const emailPattern = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;

      if (!emailPattern.test(emailValue)) {
        warning.classList.remove("d-none");
      } else {
        warning.classList.add("d-none");
      }
    });

## Credits

Bootstrap: For the responsive framework and components.
Google Fonts: For the "Be Vietnam Pro" font.
Bootstrap Icons: For the icons used in the project.
