# Accessible Design Co. - Responsive and Accessible Web Page Project

This repository contains my submission for the Accessible Web Design Skill-Based Assessment. It demonstrates a well-structured, responsive, and accessible web page built using the HTML and CSS techniques I've learned throughout the course.

---

## 📋 Project Overview

### Semantic HTML Structure
* Used landmark HTML elements (<header>, <nav>, <main>, <section>, <article>, <footer>) instead of generic <div> containers to create meaningful document structure.
* Implemented a logical heading hierarchy, starting with <h1> in the hero section, <h2> for major sections, and <h3> for individual cards and service items.

## 🎨 Layout & Responsive Design

### Flexbox Implementation
* Header & Navigation: Built with Flexbox to align the logo and navigation links. On desktop, items sit inline with space between; on smaller screens (under 600px), the layout gracefully stacks into a centered column.

### CSS Grid Implementation
* Services Section: Uses CSS Grid with adaptive column layouts:
  * Desktop (1025px+): 3-column layout (repeat(3, 1fr))
  * Tablet (601px–1024px): 2-column layout for better readability
  * Mobile (≤600px): Single-column layout for easy scrolling on phones

## ♿ Accessibility Features

### ARIA Roles & Landmarks
* Added role="navigation" and aria-label="Main Navigation" to the navigation bar.
* Used aria-labelledby to explicitly associate sections with their headings, improving screen reader navigation.

### Forms & Inputs
* Every form input and textarea includes an explicitly linked <label> using the for attribute.
* Used aria-describedby to connect helper text and instructions to their respective input fields.
* Required fields are visually marked with asterisks and include aria-required="true" for assistive technology.

### Keyboard Navigation & Visual Design
* Color contrast: All text, buttons, and background combinations have been checked against WCAG 2.1 AA standards using contrast checking tools to ensure readability.

### Decorative Elements
* Service icons are purely decorative and include  alt="" to prevent screen readers from announcing them unnecessarily.

## 🛠️ Technologies Used
* HTML — Semantic markup and accessibility
* CSS — Flexbox, Grid, media queries, and custom properties
* ARIA — Accessible Rich Internet Applications attributes

## ✅ Assessment Criteria Met
☑ Semantic HTML structure with proper heading hierarchy
☑ Responsive design using Flexbox and CSS Grid
☑ Media queries for multiple screen sizes
☑ ARIA roles, labels, and descriptions
☑ Accessible forms with proper labels and error handling
☑ Keyboard focus management
☑ Sufficient color contrast ratios
☑ Decorative vs. meaningful image handling

## Reflection Questions
1. What accessibility challenges did you face, and how did you address them?
   Making sure that the site is functional in both desktop and mobile was kind of tricky for me but I was able to get it right by playing around with the settings.
2. How did you ensure that your design was responsive and accessible to all users?
   By setting a media inquiry as well as making sure that the width's and heights of items were not hard set.
3. What tools or resources did you find most helpful during this project?
   I used Google to look up more info on some of the topics we've learned in class, as well as my classmates.
