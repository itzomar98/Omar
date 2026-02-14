# Omar Aldurra - Portfolio Website

A professional, responsive portfolio website for Omar Aldurra, showcasing his expertise in No-Code Development, AI Implementation, and UI/UX Design.

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended) if you want to make changes

### Installation & Local Development
1.  **Clone or Download** this repository.
2.  **Open** the project folder in your terminal.
3.  **Install Dependencies**:
    ```bash
    npm install
    ```
4.  **Run Development Server**:
    ```bash
    npm run dev
    ```
5.  Open the local URL (usually `http://localhost:5173`) in your browser.

## 🎨 Customization

### Personal Information
- Edit `index.html` to update your bio, contact details, or experience.
- Replace the placeholder image in the hero section:
    - Add your photo to the `assets/` folder (create one if it doesn't exist).
    - Update the `<img>` src in `index.html` (line 62).

### Colors & Styling
- Open `styles.css` and modify the CSS Variables at the top of the file to change the color scheme.
    ```css
    :root {
        --primary: #2563eb;  /* Change this hex code */
        /* ... */
    }
    ```

### Resume Download
- Place your PDF resume in an `assets/` folder.
- Rename it to `Omar_Aldurra_CV.pdf` or update the link in `index.html` (line 45).

## 📱 Features

-   **Responsive Design**: Works seamlessly on mobile, tablet, and desktop.
-   **Modern Theme**: "Tech Professional" color scheme (Blue/Purple/Green).
-   **Interactive Elements**:
    -   Smooth scrolling navigation.
    -   Mobile hamburger menu.
    -   Scroll animations (fade-in effects).
    -   Hover effects on cards and buttons.

## 📦 Deployment

You can deploy this website for free using **Vercel**, **Netlify**, or **GitHub Pages**.

### Vercel (Recommended)
1.  Install Vercel CLI: `npm i -g vercel`
2.  Run `vercel` in the project directory.
3.  Follow the prompts to deploy.

### GitHub Pages
1.  Push this code to a GitHub repository.
2.  Go to Settings > Pages.
3.  Select the `main` branch and save.

## 📄 License
This project is for personal use.

---
**Created for Omar Aldurra**
