# Interactive Valentine's Web Application

A customizable, interactive front-end web application designed to deliver a personalized, romantic experience. Built with a focus on modularity,
the project separates configuration, logic, and styling, allowing users to easily generate their own custom web page without altering the core logic.

## 🚀 Features

* **Dynamic DOM Manipulation:** Elements and questions are updated dynamically based on user interaction.
* **Interactive UI Elements:** Includes an evasive "No" button that calculates random viewport coordinates to escape the cursor.
* **Custom Range Slider (Love Meter):** A specialized input range slider that dynamically scales beyond 100%, updating the UI layout and DOM nodes in real-time.
* **CSS Animations:** Features smooth transitions, keyframe animations (floating emojis, bouncing text), and a final particle-like explosion effect.
* **Audio Integration:** Includes a background music player with autoplay handling and interactive toggle controls.
* **Theming Engine:** Reads user preferences from a JavaScript configuration object and injects them into the DOM as CSS variables.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:** Custom properties (variables), Flexbox, CSS animations, and gradient styling.
* **Vanilla JavaScript (ES6+):** Event listeners, object manipulation, and dynamic styling application.

## 📁 Project Structure

* `config.js`: Centralized configuration file for text, colors, emojis, and audio settings.
* `index.html`: Main document structure.
* `styles.css`: Core stylesheet including animations and custom UI elements.
* `script.js`: Main application logic and event handling.
* `theme.js`: Utility script to bind configuration settings to CSS variables.

## 💻 Local Execution

1. Clone this repository to your local machine.
2. Open `index.html` directly in any modern web browser.
3. Edit `config.js` to customize the text, colors, and media content.

## 🌐 Live Demo

The application can be hosted statically. A live demo is available at: **[https://riccardogpt.github.io/valentine/]**
