# Navigation Component

This repository contains a Vue.js navigation component that provides a responsive navbar with a mega menu and mobile menu functionality.

## Preview

### Desktop View
![Desktop Navbar Preview](https://github.com/AroshaRavishan/Navbar-with-Mega-Menu-Vue3/blob/main/Navbar%20Preview.png)

### Mega Menu
![Mega Menu Preview](https://github.com/AroshaRavishan/Navbar-with-Mega-Menu-Vue3/blob/main/Mega%20Menu%20Preview.png)

### Mobile View
![Mobile View Preview](https://github.com/AroshaRavishan/Navbar-with-Mega-Menu-Vue3/blob/main/Mobile%20View.png)

### Drawer Menu
![Drawer View Preview](https://github.com/AroshaRavishan/Navbar-with-Mega-Menu-Vue3/blob/main/Navabr%20With%20Drawer%20Menu.png)


### Custom Mega menu with background Overlay
![Custom Mega menu with background Overlay](https://github.com/AroshaRavishan/Navbar-with-Mega-Menu-Vue3/blob/main/Custom%20Nabar%20with%20Background%20Overlay.png)

## Features

- Responsive design that adapts to different screen sizes
- Mega menu for desktop view
- Collapsible mobile menu for smaller screens
- Smooth transitions for menu toggling
- Integration with vue-router for navigation

## Component Structure

The navigation component consists of the following main parts:

1. Desktop Navigation
   - Logo
   - Mega Menu
   - Navigation Links
   - Login and Register buttons

2. Mobile Navigation
   - Logo
   - Hamburger menu toggle
   - Collapsible menu with navigation links

3. Mega Menu
   - Multiple columns of links
   - Centered layout

## Functionality

### Toggle Menu

The `toggleMenu` function handles the opening and closing of the mobile menu. It toggles the `isOpen` ref value.

### Close Mobile Menu

The `closeMobileMenu` function is used to close the mobile menu when a link is clicked. It sets the `isOpen` ref value to false.

### Mounted Hook

The `onMounted` hook initializes Flowbite, a utility-first CSS framework, when the component is mounted.

## Styling

The component uses Tailwind CSS classes for styling, providing a clean and responsive design. Custom transitions are applied to the mobile menu for smooth opening and closing animations.

## Usage

To use this component, import it into your Vue.js application and place it at the top of your page layout. Ensure that you have the necessary dependencies installed, including Vue.js, vue-router, and Tailwind CSS.

## Customization

You can customize the component by:
- Modifying the Tailwind CSS classes
- Changing the logo image
- Adjusting the mega menu content
- Updating the navigation links

## Dependencies

- Vue.js 3
- vue-router
- Tailwind CSS
- Preline (for additional UI components)

Make sure to install and configure these dependencies in your project before using this component.
