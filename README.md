# Interactive Web Template with Smooth Scrolling Navigation

This project introduces an **interactive web template** designed with smooth scrolling navigation. Using a combination of **HTML**, **CSS**, and **JavaScript**, it ensures a **seamless user experience** for modern web applications, enhancing the interaction and layout of the website.

The template allows users to effortlessly navigate between different sections of a page with smooth scrolling transitions, while ensuring responsiveness and dynamic interactions through clean and efficient code.

## 🛠️ Features
- **Smooth Scrolling Navigation**: Effortlessly scroll to specific sections of the webpage with a single click or tap.
- **Interactive Navigation Links**: Navigation elements highlight and guide users to:
    - Home
    - About
    - Skills
    - Projects
    - Contact
- **Customizable Animations**: Dynamic hover effects and responsive layouts adapt to various devices.
- **Optimized Design for Performance**: Implements lightweight code for a smooth user experience without sacrificing speed.

## 📋 Requirements
- **HTML5**: Structure your content with semantic markup.
- **CSS3**: Apply styles, hover effects, and animations for a visually appealing layout.
- **JavaScript**: Enable interactive functionality, such as smooth scrolling with `scrollIntoView`.

## 🚀 How to Use
Setup the Project
Open the `index.html` file in any modern web browser.
Customize the content within the <section> tags to fit your requirements.
JavaScript Implementation
Include the scrollToSection function for smooth scrolling:

### JavaScript Implementation

Include the scrollToSection function for smooth scrolling:
javascript
```bash
    function scrollToSection(sectionId) {
        const targetSection = document.getElementById(sectionId);
        targetSection.scrollIntoView({
            behavior: 'smooth',
            block: 'start'
        });
    }
```
### Navigation Links Example

Add navigation items to the `nav` tag:
```bash
<nav>
    <p onclick="scrollToSection('home')">Home</p>
    <p onclick="scrollToSection('about')">About</p>
    <p onclick="scrollToSection('skills')">Skills</p>
    <p onclick="scrollToSection('projects')">Projects</p>
    <p onclick="scrollToSection('contact')">Contact</p>
</nav>
```

### Clone the Repository
```bash
    https://github.com/MohanCheenu/Portfolio-Using-HTML-CSS-JS.git
```

## 🎥 Showcase

https://github.com/user-attachments/assets/a718974f-399c-4026-b850-cf20e25f923c


## 👨‍💻 Contact
If you have any questions or suggestions, feel free to reach out to:

- Author: Mohan M
- Email: mohancheenu02@gmail.com
- GitHub: MohanCheenu
