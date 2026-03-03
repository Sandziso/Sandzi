
```markdown
# 🚀 Sandziso Mamba – Full-Stack Developer Portfolio

This is the source code of my personal portfolio website – a modern, responsive, and interactive showcase of my skills, projects, and professional background as a full‑stack developer. The site is built with HTML, CSS, JavaScript (jQuery), and leverages several popular libraries to create a smooth, engaging user experience.

🔗 **Live demo**: [https://sandzi.netlify.app

---

## ✨ Features

- **Dark / Light mode toggle** with persistent user preference (localStorage)
- **Interactive particle background** (particles.js) on the home section
- **Typed introduction** (Typed.js) highlighting areas of expertise
- **Smooth scroll animations** (ScrollReveal)
- **3D tilt effect** on project cards (VanillaTilt)
- **Dynamic project loading** from a local `projects.json` file
- **Animated skill progress bars** that fill when scrolled into view
- **Fully functional contact form** powered by EmailJS (no backend required)
- **Mobile‑friendly navigation** with hamburger menu
- **Scroll‑to‑top button** and active section highlighting
- **Preloader** for a polished first impression

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with CSS variables for theming)
- **JavaScript (ES6)** + **jQuery**
- [Typed.js](https://github.com/mattboldt/typed.js/)
- [Particles.js](https://vincentgarreau.com/particles.js/)
- [VanillaTilt.js](https://micku7zu.github.io/vanilla-tilt.js/)
- [ScrollReveal](https://scrollrevealjs.org/)
- [EmailJS](https://www.emailjs.com/)
- [Font Awesome](https://fontawesome.com/) & [Bootstrap Icons](https://icons.getbootstrap.com/)

---

## 🧪 Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/Sandziso/portfolio.git
cd portfolio
```

2. Open the project

You can simply open index.html in your browser, but to avoid CORS issues when loading projects.json, it is recommended to use a local development server.

Recommended: Use Live Server (VS Code)

· Install the Live Server extension
· Right‑click index.html and select Open with Live Server

Alternative: Use Python HTTP server

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

3. Make the contact form work (optional)

The contact form uses EmailJS. To receive messages, you need to replace the keys with your own:

1. Sign up at EmailJS
2. Create an email service and a template.
3. In assets/js/script.js, update the following lines:
   · emailjs.init("YOUR_PUBLIC_KEY")
   · In the emailjs.sendForm call, replace 'service_nsl49kr' and 'template_92qbg1k' with your own service ID and template ID.

4. Customize your content

· Projects: Edit assets/data/projects.json – add/remove projects and ensure the corresponding images are placed in assets/images/projects/.
· Personal info: Update text, links, and the resume PDF (Sandziso_Mamba_CV.pdf) directly in index.html.
· Profile image: Replace assets/images/profile2.jpg.
· Styling: Modify assets/css/style.css – CSS variables make it easy to change the color scheme.

---

🚀 Deployment

The site is completely static and can be deployed to any static hosting service.

GitHub Pages

1. Push the repository to GitHub.
2. Go to Settings > Pages.
3. Under Branch, select main (or master) and the root folder.
4. Click Save. Your site will be published at https://<username>.github.io/<repository>.

Netlify / Vercel

1. Drag and drop the project folder into Netlify Drop, or connect your Git repository.
2. The site will be automatically built and deployed.

---

📁 Project Structure

```
portfolio/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── images/
│   │   ├── profile2.jpg
│   │   ├── projects/
│   │   │   └── (project images)
│   │   └── educat/
│   │       └── college.jpg
│   ├── data/
│   │   └── projects.json
│   └── Sandziso_Mamba_CV.pdf
└── README.md
```

---

📄 License

This project is open source and available under the MIT License.

---

🙌 Acknowledgements

· All the amazing open‑source libraries listed above.
· Icons by Font Awesome and Bootstrap Icons.
· Inspiration from countless developer portfolios across the web.

---

📬 Contact

Feel free to reach out if you have any questions or opportunities!

· Email: mlungisimamba01@gmail.com
· LinkedIn: linkedin.com/in/mlungisimamba
· GitHub: github.com/Sandziso

```
```
