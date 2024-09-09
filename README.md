# Responsive Pricing Table Webpage

This repository contains a fully responsive pricing table webpage built using HTML5 and CSS3. It features a modern, scalable UI for showcasing multiple pricing tiers with distinct feature sets. The project leverages semantic HTML for structure and clean, modular CSS for styling and layout.

## Overview

The pricing table is designed to display three tiers: **Personal**, **Small Team**, and **Enterprise**. Each tier includes a list of features, an associated price, and interactive buttons that users can click to sign up or start a free trial. The design uses Flexbox for flexible layouts and media queries to ensure responsiveness across devices.

### Core Functionality

- **HTML5 Markup**: 
  - Semantic and accessible HTML structure that adheres to modern web standards.
  - Use of `<section>`, `<article>`, and `<ul>` elements to create logical blocks for pricing plans.
  
- **CSS3 Styling**:
  - **Reset Styles**: Eric Meyer's CSS reset is included to ensure consistent styling across different browsers.
  - **Flexbox Layout**: The CSS utilizes a Flexbox-based grid system for arranging the pricing plans horizontally on larger screens and vertically on smaller ones.
  - **Responsive Design**: Breakpoints defined using media queries allow the layout to adapt to different screen sizes, ensuring a seamless experience on mobile, tablet, and desktop devices.
  - **Hover and Focus States**: CSS transitions are applied to the pricing buttons to enhance user interaction.

### Technical Features

1. **Reset Stylesheet**:
   - A CSS reset is applied to standardize the layout across all browsers by removing default margin, padding, and other inconsistencies across HTML elements【6†source】.
   
2. **Flexbox for Responsive Design**:
   - The main container (`.panel`) utilizes Flexbox for arranging the pricing tiers. On screens wider than 900px, the plans are aligned horizontally. On narrower screens, the layout switches to a vertical arrangement to improve readability and accessibility【6†source】.

3. **Pricing Plan Layout**:
   - Each pricing plan is housed in a `div` with the `.pricing-plan` class. Elements like the header, image, feature list, price, and button are structured within, following a consistent design to improve UX/UI clarity【5†source】【6†source】.
   
4. **Responsive Breakpoints**:
   - Media queries target screen widths of 900px or larger to apply different styles, ensuring that the content remains visually appealing and easy to navigate on both small and large screens【6†source】.
   
5. **Scalable Font and Typography**:
   - The webpage makes use of the `Open-Sans` font loaded via Google Fonts. Font sizes are defined in `rem` units for scalability across various screen resolutions.

### Code Structure

- **index.html**: 
  - Includes the semantic HTML structure for the webpage. This file contains three main sections, each representing a pricing plan (Personal, Small Team, Enterprise). Each section includes:
    - A header for the plan name.
    - An image placeholder for visual enhancement.
    - A feature list with descriptive points.
    - A CTA button with hover effects.

- **app.css**:
  - Contains the CSS for styling the pricing plans and layout:
    - **Base Styles**: Applies a global reset and defines common properties like fonts, colors, and spacing.
    - **Panel & Pricing Plan Styles**: CSS classes for organizing the layout of the pricing plans, including hover effects, transitions, and layout adjustments for different screen sizes.

### File Breakdown

1. `index.html`: 
   - This file handles the overall layout and structure of the page. It includes three main sections for the pricing plans, feature lists, and buttons for user interaction.
  
2. `app.css`: 
   - Defines the visual presentation of the pricing plans, including color schemes, typography, layout, and transitions for interactive elements.

### Key CSS Concepts

- **Flexbox**: Utilized for creating flexible layouts. Adjusts the flow of content between horizontal and vertical orientations based on screen size.
- **CSS Reset**: Ensures cross-browser consistency by neutralizing default styling.
- **Media Queries**: Adjusts the layout and styles depending on the viewport size to ensure responsiveness.
- **Transitions**: Smooth hover and focus effects on interactive elements like buttons to improve user engagement.
