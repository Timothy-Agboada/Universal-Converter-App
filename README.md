## 🚀 30-Day Coding Challenge: Day 14

This project is the fourteenth entry in my 30-day coding challenge. Today's goal was to expand on the core concepts of React by building a more complex, multi-purpose application. This project demonstrates component reusability, state management, and dynamic theming.

### 📖 Project Overview

This is a modern and versatile unit converter application built entirely with React. It provides a single, clean interface to convert between common units for Temperature (Celsius/Fahrenheit), Weight (Kilograms/Pounds), and Length (Meters/Feet). The application features an intuitive tab-based navigation and a dynamic color scheme that changes to match the selected converter type, enhancing the user experience.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-21-2025 22-12-05](https://github.com/user-attachments/assets/670b58c7-dd4b-4f20-99b7-2b6e5cccc655)


### 🌟 Key Features

* **Multi-Purpose Converter:** A single application that handles three different types of unit conversions: Temperature, Weight, and Length.
* **Dynamic Theming:** The entire UI's color scheme and background change smoothly when switching between converter types, providing excellent visual feedback.
* **Reusable Components:** Built with a reusable `UnitInput` component, showcasing a core principle of React for creating scalable and maintainable UIs.
* **Component Composition:** Each specific converter (e.g., `TemperatureConverter`) is composed of smaller, reusable `UnitInput` components.
* **Lifted & Synchronized State:** State is managed within each converter component to keep the input fields perfectly synchronized. Typing in one field instantly updates the other.
* **Modern UI/UX:** A clean, intuitive interface featuring tab-style navigation, modern input fields, and a responsive design that works great on all devices.

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons in the navigation tabs.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/universal-converter-app.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd universal-converter-app
    ```
3.  **Open the `index.html` file in your web browser:**
    * You can simply double-click the `index.html` file. The CDN links will handle loading React and Babel automatically.

### 🎯 Learning Objectives

This project was a significant step in practicing intermediate React concepts:

* **Component Reusability:** Designing and implementing a generic `UnitInput` component that can be used across different contexts.
* **Component Composition:** Building larger, feature-specific components (`TemperatureConverter`, `WeightConverter`) out of smaller, reusable ones.
* **State Lifting Principle:** Understanding how to keep the state of sibling components in sync by lifting it to their closest common parent.
* **Conditional Rendering:** Dynamically rendering the active converter component based on the application's state.
* **Props:** Passing data and functions (callbacks) from parent components to child components to manage state and handle events.
* **Dynamic Styling in React:** Changing CSS classes and theming an application based on its state.
