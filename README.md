# 📅 Daily Planner Dashboard

A clean, modern, and responsive daily planning interface built with **HTML5 and CSS3**. This project focuses on helping users organize daily activities, identify important priorities, structure their schedules, and capture notes through a well-organized dashboard layout.

Developed as part of practical front-end web development training, the project demonstrates semantic HTML, CSS Grid, Flexbox, responsive design, form styling, and modern user interface principles.

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Implementation Highlights](#-implementation-highlights)
- [Responsive Design](#-responsive-design)
- [Accessibility and Best Practices](#-accessibility-and-best-practices)
- [Learning Objectives](#-learning-objectives)
- [Limitations](#-limitations)
- [Future Improvements](#-future-improvements)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## 🎯 Overview

The **Daily Planner Dashboard** is a front-end web project designed to provide a structured space for planning and organizing everyday activities.

The interface brings essential planning elements together in one place, including daily priorities, a task checklist, a time-based schedule, and a dedicated notes area. Its layout is designed to make information easy to scan while maintaining a consistent experience across desktop, tablet, and mobile screens.

The project uses **CSS Grid** to organize the main dashboard layout and **Flexbox** to align individual interface elements. Semantic HTML5 provides the document structure, while CSS3 handles the visual presentation and responsive behavior.

The primary goal is to demonstrate how a practical, visually polished planning interface can be built using foundational web technologies.

## ✨ Features

- **Daily Priorities:** A dedicated section for highlighting the most important tasks of the day.
- **Interactive Task Checklist:** HTML checkboxes allow users to mark tasks as completed during their current page session.
- **Time-Blocked Schedule:** Organized time slots help users structure activities throughout the day.
- **Notes and Brain Dump:** A text area provides space for recording ideas, reminders, and other important information.
- **Responsive Dashboard Layout:** CSS Grid and media queries support layouts that adapt to different screen sizes.
- **Flexible Component Alignment:** Flexbox helps organize content, controls, labels, and individual card elements.
- **Modern User Interface:** Clean spacing, consistent typography, rounded corners, subtle shadows, and a coordinated color palette create a polished appearance.
- **Keyboard-Friendly Controls:** Properly labeled form elements and visible focus styles support accessible interaction.
- **Maintainable Code Structure:** HTML markup and CSS styling are separated into dedicated files for easier updates and debugging.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Provides semantic structure and planning interface elements. |
| CSS3 | Controls typography, colors, spacing, borders, and visual styling. |
| CSS Grid | Organizes the main dashboard and card layout. |
| Flexbox | Aligns content and distributes space within individual components. |
| Media Queries | Adjust the layout for different viewport sizes. |
| CSS Pseudo-Classes | Style interaction states such as `:hover`, `:focus-visible`, and `:checked`. |
| Git and GitHub | Support version control and repository hosting. |

## 📁 Project Structure

```text
daily-planner-dashboard/
│
├── index.html      # Main HTML document and dashboard structure
├── styles.css      # Styling, layout, and responsive design
└── README.md       # Project documentation
```

## 🚀 Getting Started

Follow these steps to run the project on your local machine.

### Prerequisites

You need:

- A modern web browser, such as Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari.
- A code editor, such as Visual Studio Code, if you want to inspect or modify the source files.
- Git, if you plan to clone the repository from GitHub.

No package manager, framework, or build tool is required.

### 1. Clone the Repository

Replace the placeholder with the actual URL of your GitHub repository.

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd daily-planner-dashboard
```

### 3. Open the Project

Open `index.html` directly in your preferred web browser.

Alternatively, open the project folder in Visual Studio Code and use the Live Server extension to preview your changes while developing.

### 4. Customize the Dashboard

- Edit `index.html` to modify task labels, schedule entries, priorities, and notes sections.
- Edit `styles.css` to customize the color palette, typography, spacing, card styles, and responsive breakpoints.

Save your changes and refresh the browser to view the updated interface.

## 💡 Implementation Highlights

### 1. Semantic HTML5

Semantic HTML elements provide meaningful structure and improve the readability and maintainability of the page.

Elements such as `<header>`, `<main>`, `<section>`, `<nav>`, and `<footer>` can be used where appropriate to organize the dashboard.

Form controls, including checkboxes and text areas, provide native browser functionality without requiring JavaScript.

### 2. CSS Grid for Dashboard Layout

CSS Grid is well suited to arranging multiple dashboard sections into rows and columns.

Example:

```css
.dashboard {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.5rem;
}
```

This example creates a two-column layout with consistent spacing between dashboard sections. The actual number of columns can be adjusted to suit the design.

### 3. Flexbox for Component Alignment

Flexbox helps align content within individual cards and interface components.

Example:

```css
.card-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}
```

This layout aligns the header content vertically and distributes available horizontal space between its children.

### 4. Responsive Design with Media Queries

Media queries allow the layout to adapt when the viewport becomes narrower.

Example:

```css
@media (max-width: 768px) {
  .dashboard {
    grid-template-columns: 1fr;
  }
}
```

This example changes the dashboard to a single-column layout on screens with a viewport width of 768 pixels or less.

### 5. Native HTML Form Controls

HTML checkboxes and text areas provide basic built-in interaction.

For example, checkboxes can be selected to visually indicate completed tasks. CSS can style their checked state using the `:checked` pseudo-class.

These native controls are useful for demonstrating interactive styling while keeping the project JavaScript-free.

## 📱 Responsive Design

The dashboard is intended to remain readable and usable across a range of screen sizes.

Responsive design techniques may include:

- **Desktop:** A multi-column dashboard layout that uses available screen space efficiently.
- **Tablet:** Adjusted column arrangements and spacing for medium-sized screens.
- **Mobile:** A single-column layout that keeps cards and controls easy to access.
- **Flexible Sizing:** Relative units such as `%`, `rem`, and `minmax()` help prevent rigid layouts.
- **Responsive Typography:** Appropriate font sizes and line heights support readability on smaller displays.
- **Consistent Spacing:** CSS Grid gaps, Flexbox alignment, and reusable spacing values help maintain visual consistency.

The final layout should be tested at multiple viewport widths to identify horizontal overflow, cramped content, and other usability issues.

## ♿ Accessibility and Best Practices

Accessibility and maintainability are important considerations when building a usable web interface.

Recommended practices include:

- Use semantic HTML elements according to their intended purpose.
- Maintain a logical heading hierarchy.
- Associate form labels with their corresponding controls.
- Ensure interactive elements can be reached and used with a keyboard.
- Provide visible focus indicators for keyboard navigation.
- Maintain sufficient contrast between text and background colors.
- Use readable font sizes and adequate spacing.
- Avoid relying on color alone to communicate task status.
- Keep CSS organized and use consistent naming conventions.
- Test the layout at different screen sizes and browser zoom levels.

## 🎓 Learning Objectives

This project provides practical experience with the following front-end development concepts:

- Writing structured and semantic HTML5.
- Building page layouts with CSS Grid.
- Aligning interface components using Flexbox.
- Creating responsive layouts with CSS media queries.
- Styling native HTML form controls.
- Using CSS pseudo-classes to represent interaction states.
- Applying consistent typography, spacing, and color systems.
- Improving accessibility and keyboard usability.
- Separating structure from presentation.
- Organizing and documenting a small front-end project for GitHub.

## ⚠️ Project Limitations

This version is built with HTML5 and CSS3 only. It demonstrates interface design and native browser interactions rather than a fully automated productivity application.

- Checkboxes can be selected, but task completion does not automatically update other dashboard elements.
- Tasks and notes are not automatically saved across page reloads.
- The schedule does not automatically generate reminders or notifications.
- Priorities and task lists do not automatically reorder or update.
- No automatic time tracking or productivity calculations are included.

These limitations are intentional for a project focused on HTML and CSS fundamentals. Persistent storage and more advanced functionality would require JavaScript or an appropriate back-end service.

## 🔮 Future Improvements

Possible enhancements for future versions include:

- **Persistent Task Management:** Save tasks and notes between sessions using browser storage.
- **Task Filtering:** Separate pending, completed, and high-priority tasks.
- **Automatic Scheduling:** Add functionality for creating and rearranging schedule entries.
- **Date Navigation:** Allow users to plan and review different days.
- **Reminders:** Introduce notifications for upcoming activities.
- **Progress Tracking:** Display task completion summaries and daily progress.
- **Theme Customization:** Add light and dark themes.
- **Enhanced Accessibility:** Conduct keyboard, contrast, and screen-reader testing.
- **Deployment:** Publish the dashboard through GitHub Pages or another static hosting platform.

These improvements are proposed ideas, not features included in the current HTML and CSS implementation.

## 🤝 Contributing

Suggestions, feedback, and improvements are welcome.

To contribute:

1. Fork the repository.
2. Create a feature branch.

   ```bash
   git checkout -b feature/your-improvement
   ```

3. Make your changes and test the interface.
4. Commit your changes.

   ```bash
   git commit -m "Improve dashboard layout"
   ```

5. Push the branch to your fork.

   ```bash
   git push origin feature/your-improvement
   ```

6. Open a pull request describing your changes.

Please keep contributions focused, readable, accessible, and consistent with the project's HTML and CSS approach.

## 📄 License

No license has been specified for this project yet.

If you plan to distribute the project as open-source software, consider selecting an appropriate license and adding a `LICENSE` file to the repository. Until then, do not assume that the source code is available for unrestricted reuse or redistribution.

## 👨‍💻 Author

**Stephen Oyugi**

- GitHub: [@Regalson001](https://github.com/Regalson001)

---

<p align="center">
  Built with HTML5 and CSS3 as part of a front-end web development journey.
</p>

<p align="center">
  <strong>Plan with purpose. Build with consistency. Improve every day.</strong>
</p>
