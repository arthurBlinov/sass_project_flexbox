# SASS_PROJECT_FLEXBOX

## Project Overview
This project demonstrates the use of Sass (a CSS preprocessor) and Flexbox (a modern layout system) to create a responsive, modular, and visually appealing web page. The project is structured to support scalability and maintainability through modular Sass files, semantic HTML, and clean design principles.

## Features

### Responsive Design:
- Media queries ensure the page adapts seamlessly to various screen sizes.
- Mobile-friendly layouts with optimized spacing and font scaling.

### Modular Sass Structure:
- Reusable variables, mixins, and nested rules to organize and manage styles efficiently.

### Flexbox Layout:
- Dynamic alignment and spacing for layout containers and elements.
- Simplified alignment of components like headers, sidebars, and main content.

### Interactive Elements:
- Buttons, navigation links, and forms styled with hover and focus effects.

### SVG Integration:
- Scalable vector graphics used for icons, ensuring high-quality visuals at any resolution.

## File Structure

## HTML

The main HTML file (index.html) contains the following sections:

### Header:
- Includes a search bar with an SVG icon and user navigation with profile photos and notifications.

### Sidebar:
- Navigation links with SVG icons (e.g., "Hotel," "Flight," "Tours") and an active state indicator.

### Main Content:
- **Gallery:** Displays images of the hotel.
- **Overview:** Highlights the hotel name, star rating, location, and guest reviews.
- **Details:** Contains a description, feature list, and user recommendations.
- **User Reviews:** Displays user-submitted reviews with photos, names, and ratings.

## Sass/CSS
- The main Sass file (main.scss) compiles into css/main.css. Key features include:

### Global Variables:
- Colors, shadows, and breakpoints for consistent styling.

### Global Resets:
- box-sizing: border-box; applied universally.
- Margin and padding reset for all elements.

### Layout Styles:
- Flexbox used to align and space containers and components.
- Media queries for responsive layouts.

### Component Styles:
- Buttons, icons, and lists styled with interactive effects (e.g., hover, focus).
- Dynamic animations (e.g., pulsating button focus).

### Reusable Elements:
- Lists and features styled for readability.

## Setup Instructions

### Prerequisites
**Node.js:** Ensure Node.js and npm are installed.
**Sass:** node-sass installed globally or locally in the project.

## Installation

### Clone the repository:
- git clone https://github.com/arthurBlinov/sass_project_flexbox.git

### Navigate to the project directory:
- cd sass_flexbox

### Install dependencies:
- npm install

### Start the Sass compiler:
- npm run sass

- Open index.html in your browser to view the page (Live Server, for example).

