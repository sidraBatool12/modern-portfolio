# Sidra Batool | Personal Portfolio

Welcome to my personal portfolio! This project showcases my skills, projects, and experience in web development. It is fully responsive, interactive, and features smooth scroll-based animations with modern design.

---

## Table of Contents

- [About Me](#about-me)
- [Skills](#skills)
- [Projects](#projects)
- [Animations](#animations)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Contact](#contact)
- [License](#license)

---

## About Me

Hi! I am **Sidra Batool**, a **Computer Science student** and aspiring **Full-Stack Developer**.  
I enjoy creating **interactive websites** with smooth animations, clean layouts, and responsive design.  
Currently, I focus on **front-end development** with plans to learn **backend technologies** in the near future.

---

## Skills

### Front-End
- HTML5, CSS3, Bootstrap
- JavaScript (ES6+)
- React.js, Next.js

### Back-End (Learning)
- Node.js
- Python
- Databases: MySQL, MongoDB

### Programming Languages
- C, C++, Python

### Other Skills
- Responsive Design
- Smooth Scroll Animations
- Intersection Observer for scroll-based effects

---

## Projects

Here are some of my notable projects:

1. **Portfolio Website** – Interactive personal portfolio with smooth scroll animations.  
2. **Project 2** – Brief description of your second project with technologies used.  
3. **Project 3** – Brief description of your third project with technologies used.  

> All projects are responsive and visually appealing, focusing on smooth user experience and modern design.

---

## Animations

The portfolio uses **scroll-based animations** to enhance interactivity:

- **Fade-in Effects** – Elements appear smoothly as the user scrolls.  
- **Intersection Observer API** – Used for performant scroll-based triggers.  
- **CSS Transitions** – Smooth transitions for all animated elements.  

**Example CSS:**
```css
.reveal {
  opacity: 0;
  transform: translateY(20px);
  transition: all 0.7s ease-out;
}

.reveal.show {
  opacity: 1;
  transform: translateY(0);
}


const reveals = document.querySelectorAll('.reveal');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if(entry.isIntersecting) {
      entry.target.classList.add('show');
    }
  });
});

reveals.forEach(el => observer.observe(el));



const reveals = document.querySelectorAll('.reveal');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if(entry.isIntersecting) {
      entry.target.classList.add('show');
    }
  });
});

reveals.forEach(el => observer.observe(el));


const reveals = document.querySelectorAll('.reveal');

const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if(entry.isIntersecting) {
      entry.target.classList.add('show');
    }
  });
});

reveals.forEach(el => observer.observe(el));
