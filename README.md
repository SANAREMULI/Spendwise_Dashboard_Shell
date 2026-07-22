index.html
<img width="893" height="431" alt="image" src="https://github.com/user-attachments/assets/3eef53fc-fdeb-47dc-9c98-04e9067053ce" />
SpendWise Dashboard Shell

## Overview

SpendWise Dashboard Shell is a responsive financial dashboard built using HTML5 and CSS3. This project focuses on creating a modern dashboard layout using CSS Grid and Flexbox without adding functionality. The dashboard serves as the foundation for a future expense tracking application.

---

## Features

- Responsive dashboard layout
- Sidebar navigation
- Header with welcome section
- Six financial category cards
- CSS Grid page layout
- Flexbox inside components
- CSS Custom Properties (Variables)
- Responsive design
- Hover and keyboard focus animations
- Automatic Dark Mode support

---

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Variables
- Google Fonts (Poppins)

---

## Project Structure

```
spendwise-dashboard/
│
├── index.html
├── style.css
└── README.md
```

---

## Files

### index.html

Contains the dashboard structure including:

- Sidebar
- Header
- Six financial cards

---

### style.css

Contains all styling including:

- CSS Variables
- Grid Layout
- Flexbox
- Responsive Design
- Hover Animations
- Dark Theme

---

### README.md

Project documentation.

---

## Layout

### Sidebar

Provides navigation links for:

- Dashboard
- Expenses
- Reports
- Budget
- Settings

---

### Header

Displays:

- Dashboard title
- Welcome message

---

### Dashboard Cards

Displays six financial categories:

- Food
- Transport
- Rent
- Entertainment
- Savings
- Utilities

---

## CSS Concepts Applied

### CSS Grid

Used for the overall dashboard layout.

### Flexbox

Used inside:

- Sidebar
- Header
- Cards

### CSS Variables

Variables defined in the `:root` selector:

- Brand Color
- Accent Color
- Background Color
- Surface Color
- Primary Text
- Secondary Text

### Responsive Design

A media query changes the dashboard into a single-column layout below **768px**.

### Micro-interactions

Dashboard cards include:

- Hover animation
- Keyboard focus animation
- Transform
- Box shadow
- 250ms transition

### Dark Theme

Implemented using:

```css
@media (prefers-color-scheme: dark)
```

Only the CSS variables are overridden.

---

## Learning Outcomes

This project demonstrates:

- CSS Grid layouts
- Flexbox alignment
- Responsive web design
- CSS Variables
- Modern UI styling
- Dark Mode implementation
