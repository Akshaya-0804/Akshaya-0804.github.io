# Akshaya-0804.github.io
# 💼 Akshaya's Portfolio Website

This is a personal portfolio website that showcases my profile, technical skills, and project work using modern HTML and CSS. The goal of this project is to present my work in a clean, professional, and responsive design.

---
## 🎯 Project Objectives

The primary objectives of this portfolio website project are as follows:

### 1. **Showcase Personal and Professional Information**
- To create an online presence where potential employers or collaborators can learn more about me.
- Include detailed sections on who I am, what I do, and how I can be contacted.

### 2. **Demonstrate Technical Skills**
- Highlight key programming and web development skills using progress bars and visual indicators.
- Ensure that the design and code quality reflect my understanding of front-end development best practices.

### 3. **Display Key Projects**
- Create a dedicated section to list and describe my completed academic and personal projects.
- Each project card should include a clear title and a short description of its functionality, purpose, or technology used.

### 4. **Build a Responsive Design**
- Make sure the website works well on all device sizes including desktops, tablets, and smartphones.
- Use responsive layout techniques like Flexbox and media queries.

### 5. **Enable Easy Updates and Maintenance**
- Structure HTML and CSS in a clean, modular way to make future updates and additions easy.
- Ensure content such as skills or project descriptions can be updated without restructuring the whole site.

### 6. **Host via GitHub Pages**
- Deploy the site for free using GitHub Pages to make it publicly accessible.
- Gain experience with version control and cloud deployment using Git and GitHub.

---

## 📁 Project Overview

- **Filename**: `index.html`
- **Styling**: `main.css`
- **Assets**: Images, fonts, and JavaScript for interactivity

---

## 📌 Step-by-Step Breakdown

### 1. HTML Structure (`index.html`)

The HTML file is the backbone of the website. It defines the layout and structure of each section:

#### 🔹 Header Section
- Contains logo and navigation menu
- Responsive menu toggle for mobile devices

#### 🔹 About Section
- Introduces who I am
- Lists personal details like full name, birth date, and email

#### 🔹 Skills Section
- Displays a visual progress bar for each skill
- Skills include C++, Python, SQL, HTML, CSS

#### 🔹 Portfolio Section
- Highlights multiple projects with titles and brief descriptions:
  - QR Code Generator
  - OpenAI Chatbot
  - Google App Rating Predictor
  - Smart Crime Analysis using LSTM/ARIMA

#### 🔹 Contact Section
- Provides contact details and an optional contact form

---
# 📄 Detailed Explanation of index.html and main.css

This section documents how the `index.html` and `main.css` files work together to build the portfolio website.

---

## 📝 index.html – Website Structure

The `index.html` file is responsible for structuring the content and layout of the website using semantic HTML5 elements.

### 📌 Key Sections:

#### 1. `<header>`
- Displays the website logo or name.
- Contains a navigation menu with links to sections: Home, About, Skills, Projects, and Contact.
- Includes a hamburger menu (`fa-bars`) for responsive design on smaller screens.

#### 2. `<section class="home" id="home">`
- The hero/welcome section.
- Introduces the individual with a greeting, name, and a short tagline or role (e.g., "Web Developer").

#### 3. `<section class="about" id="about">`
- Contains a profile image.
- Describes who you are, including a short bio.
- Lists personal details like:
  - Full Name
  - Birth Date
  - Email

#### 4. `<section class="skills" id="skills">`
- Displays a list of technical skills.
- Each skill is shown with a name and a progress bar indicating proficiency (e.g., C++ – 95%).

#### 5. `<section class="portfolio" id="portfolio">`
- Showcases personal projects using card-like boxes.
- Each project includes:
  - A title (e.g., "QR Code Generator")
  - A brief description or functionality

#### 6. `<section class="contact" id="contact">`
- Provides ways to get in touch (e.g., email).
- May include a simple contact form.

---
## 🎨 main.css – Styling and Design

The `main.css` file contains all the custom styles to make the site visually appealing and responsive.

### 🎯 Main Responsibilities:

#### 1. Layout and Structure
- Uses Flexbox or Grid to organize sections.
- Defines widths, margins, paddings, and alignment to keep the design clean and responsive.

#### 2. Typography
- Imports Google Fonts for custom font styling.
- Sets font sizes, weights, and line spacing for readability.

#### 3. Colors and Themes
- Sets background colors, text colors, and hover states.
- Defines a consistent color scheme across the site.

#### 4. Skill Bars
- Styles the animated skill bars in the Skills section using:
  - `.bar` or `.progress-bar` classes
  - `width` values set via inline styles or animation for visual skill levels

#### 5. Buttons and Links
- Adds hover effects for interactivity.
- Ensures buttons are styled consistently across sections.

#### 6. Responsive Design
- Includes media queries to adjust layout for:
  - Tablets
  - Mobile devices
- Adjusts font sizes, section spacing, and navigation for smaller screens.

---
## 🛠️ How to Use This Project

1. **Download or Clone** the project folder
2. Open `index.html` in your browser to view the site
3. Modify `index.html` to update content (name, skills, projects)
4. Adjust `main.css` to customize the design or theme
## 📂 Integration Summary

- **HTML** builds the content and page structure.
- **CSS** applies all the design rules and layout adjustments.
- Together, they create a responsive, user-friendly portfolio site.

---
# 🌐 Understanding GitHub Pages

## 📌 What is GitHub Pages?

GitHub Pages is a **free static site hosting service** offered by GitHub. It allows you to publish a website directly from a GitHub repository. It is especially useful for:
- Hosting personal portfolios
- Documentation for projects
- Resumes
- Static HTML/CSS/JavaScript websites

You don’t need any external hosting service or backend server to use GitHub Pages.

---

## ⚙️ How Does GitHub Pages Work?

GitHub Pages works by taking the HTML, CSS, and JavaScript files from your GitHub repository and serving them as a static website. Here's how it functions:

1. **Repository as Source**
   - You use a GitHub repository as the source of your website's code.
   - The repository can be either public or private (with GitHub Pro for private Pages).

2. **Branch and Folder Selection**
   - GitHub Pages allows you to choose which branch and folder to publish from:
     - Commonly, the `main` or `master` branch.
     - Folder options: root (`/`) or `/docs`.

3. **Automatic Publishing**
   - Once configured, GitHub automatically builds your site and hosts it at:
     ```
     https://<username>.github.io/<repository-name>/
     ```

---

## 🪜 Step-by-Step Setup

1. **Create a GitHub Repository**
   - Name it something relevant (e.g., `portfolio`).
   - Add your project files (`index.html`, `style.css`, etc.).

2. **Push Your Code to GitHub**
   - Use Git or GitHub Desktop to upload your files.

3. **Enable GitHub Pages**
   - Go to the **Settings** tab of your repo.
   - Scroll to the **Pages** section (left sidebar).
   - Choose:
     - Source: `main` branch
     - Folder: `/ (root)` or `/docs`
   - Click **Save**.

4. **Access Your Site**
   - After a few seconds, GitHub will provide a live link to your website.
   - Example: `https://username.github.io/portfolio/`

---

## ✅ Final Notes

- You can edit `index.html` to change content (bio, skills, projects).
- Customize colors, spacing, or fonts by editing `main.css`.

---

## 📬 Contact

- **Name:** Akshaya Singu  
- **Email:** [singuakshaya@gmail.com](mailto:singuakshaya@gmail.com)

---

## 📜 License

This portfolio is open for personal use or inspiration. Please give credit if using portions of the design.
