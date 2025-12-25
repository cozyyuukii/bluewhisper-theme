# 🌊 BlueWhisper Theme

> "Weaving digital tapestries with quiet focus and creative rhythm."

**BlueWhisper Theme** is a serene, minimalist personal portfolio website template. Designed with a focus on calm aesthetics and smooth motion, it features a custom "Pale Sky Blue" and "Frosted Teal" palette, making it perfect for creatives who want a peaceful digital presence.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## ✨ Features

* **Serene Visual Design:** A custom color palette defined via CSS variables, inspired by the tranquility of dawn.
* **Responsive Layout:** Fully adaptive design that works seamlessly on mobile, tablet, and desktop screens.
* **Custom Animations:**
    * **SVG Waves:** Gentle, flowing wave animations in the hero section.
    * **Ripple Effects:** Interactive ripples on buttons and links using vanilla JavaScript.
    * **Scroll Reveals:** Elements fade in and slide up gracefully as you scroll.
* **Interactive UI:**
    * Mobile-first hamburger navigation with backdrop blur.
    * Floating label contact form with real-time validation.
    * Dynamic "Back to Top" button.
* **Performance:** Built with vanilla JavaScript (no heavy frameworks) and optimized CSS for fast load times.

## 🛠️ Tech Stack

* **Structure:** Semantic HTML5
* **Styling:** CSS3 (Flexbox, Grid, CSS Variables, Keyframe Animations)
* **Scripting:** Vanilla JavaScript (ES6+)
* **Icons:** [Bootstrap Icons](https://icons.getbootstrap.com/)
* **Fonts:** [Quicksand](https://fonts.google.com/specimen/Quicksand) (Body) & [Kristi](https://fonts.google.com/specimen/Kristi) (Headers)

## 🚀 Getting Started

Since this is a static website, no build process or backend server is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/cozyyuukii/bluewhisper-theme.git](https://github.com/cozyyuukii/bluewhisper-theme.git)
    ```
2.  **Open the project:**
    Simply navigate to the folder and open `index.html` in your web browser.

## 🎨 Customization

### 1. Changing the Branding
To make this site your own, open `index.html` and replace instances of "Yuukii" with your name. Don't forget to update the `<title>` tag and the meta description!

### 2. Theming
The color scheme is managed entirely in `style.css` using CSS variables. You can drastically change the look by editing the `:root` block:

```css
:root {
    /* Current Theme: BlueWhisper */
    --clr-bg-start: #e6f0f7;       /* Pale Sky Blue - Lighter */
    --clr-bg-end: #d0e0f0;         /* Pale Sky Blue - Darker */
    --clr-primary: #a0c4ff;        /* Pale Cerulean (Main Accent) */
    --clr-secondary: #a3d8d0;      /* Frosted Teal (Secondary Accent) */
    --clr-text-dark: #3a4d6f;      /* Headings */
}
```
```
📂 Project Structure

/
├── index.html      # Main HTML structure
├── style.css       # Global styles, variables, and animations
├── script.js       # UI logic (scroll, nav, ripple effects)
└── assets/         # (Optional) Folder for images/icons

```
📄 License

This project is open source and available under the MIT License.

