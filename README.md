## Responsive Laundry Service Landing Page

## Project Overview

This project is a responsive Laundry Service Landing Page created using HTML and CSS. The webpage includes a navigation bar, hero section, call-to-action button, and a mobile-friendly navigation menu.

The design adapts to different screen sizes using CSS Media Queries and Flexbox.

---

## Features

### Desktop View
- Logo section
- Navigation links
  - Home
  - Services
  - About Us
  - Contact Us
- Username button
- Hero section with:
  - Heading
  - Description
  - Service booking button
  - Laundry image

### Mobile View
- Navigation links are hidden.
- Menu icon (☰) is displayed.
- Clicking the menu icon opens a sidebar menu.
- Sidebar menu contains:
  - Home
  - Services
  - About Us
  - Contact Us
- Built using only HTML and CSS.
- No JavaScript used.

---

## Technologies Used

- HTML5
- CSS3
- Flexbox
- Media Queries



## Folder Structure

project-folder/



index.html

style.css
README.md



## Navigation Menu Implementation

The mobile navigation menu is created using the Checkbox Hack method.

### Components Used

1. Hidden Checkbox
2. Label (Menu Icon)
3. Navigation Links Container

Example:

```html
<input type="checkbox" id="menu-toggle">

<label for="menu-toggle" class="menu-btn">
☰
</label>



