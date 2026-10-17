# Photography Gallery Website

## 📌 About the Project

This project is a simple and interactive photography gallery website created using **HTML and CSS**. It features a stylish sidebar navigation menu with icons and a full-screen photography background.

The main purpose of this project is to practice HTML structure, CSS styling, positioning, transitions, and interactive UI design without using JavaScript.

## ✨ Features

- Full-screen background image
- Interactive sidebar navigation menu
- Hamburger menu icon to open the sidebar
- Close icon to hide the sidebar
- Smooth CSS transition effects
- Navigation items with Font Awesome icons
- Social media icons
- Google Fonts integration
- Checkbox-based interaction without JavaScript

## 🛠️ Technologies Used

- **HTML5** – For the structure of the website
- **CSS3** – For styling, positioning, transitions, and sidebar animation
- **Font Awesome** – For navigation and social media icons
- **Google Fonts** – For typography

## ⚙️ How It Works

The sidebar functionality is implemented using a hidden HTML checkbox and CSS.

1. Clicking the hamburger icon activates the checkbox.
2. The CSS `:checked` pseudo-class detects the checkbox state.
3. The general sibling selector (`~`) changes the sidebar's `left` property from `-300px` to `0`.
4. Clicking the close icon unchecks the checkbox and hides the sidebar again.

**Note:** JavaScript is not required for the sidebar's open and close functionality.

## 📂 Project Structure

```text
photography-gallery-website/
├── index.html
├── style.css
└── photo.jpg
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Keep `index.html`, `style.css`, and `photo.jpg` in the same folder.
3. Open `index.html` in your web browser.
4. Click the hamburger menu icon to open the sidebar.

An internet connection is required to load the Google Fonts and Font Awesome resources from their external CDNs.

## 🎯 Learning Outcomes

- Understanding HTML elements and labels
- Connecting a checkbox with a label using the `for` attribute
- Using CSS pseudo-classes such as `:checked` and `:hover`
- Applying CSS positioning and transitions
- Using sibling selectors to create interactive UI elements
- Integrating external fonts and icon libraries

## 👨‍💻 Author

**Dileep Kumar**

Created as a practice project to strengthen HTML and CSS skills.
