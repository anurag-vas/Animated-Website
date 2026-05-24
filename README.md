🌟 Animated Website Using GSAP

An interactive and modern animated website built using HTML, CSS, JavaScript, and GSAP (GreenSock Animation Platform).
This project focuses on smooth animations, scroll effects, and engaging user experience.

🚀 Features
Smooth page load animations
Scroll-triggered animations
Animated navigation bar
Mouse movement effects
Responsive design
Modern UI/UX animations
🛠️ Technologies Used
HTML
CSS
JavaScript
GSAP Official Website
ScrollTrigger Plugin
📂 Project Structure
animated-website/
│
├── index.html
├── style.css
└── script.js
▶️ How to Run
Download or clone the project
Open the project folder
Open index.html in your browser
💡 How It Works
GSAP Animation

GSAP is used to create smooth animations for elements.

Example:

gsap.from("#nav", {
    y: -50,
    opacity: 0,
    duration: 1
});
ScrollTrigger Animation

Animations are triggered while scrolling.

gsap.registerPlugin(ScrollTrigger);

gsap.to("#nav", {
    backgroundColor: "#000",
    height: "110px",
    scrollTrigger: {
        trigger: "#nav",
        scroller: "body",
        start: "top -10%",
        end: "top -11%",
        scrub: 1
    }
});
Mouse Follower Effect
window.addEventListener("mousemove", function(dets) {
    document.querySelector("#minicircle").style.transform =
    `translate(${dets.clientX}px, ${dets.clientY}px)`;
});
📚 Concepts Learned

This project helps beginners learn:

GSAP Animations
ScrollTrigger Plugin
Timeline Animations
DOM Manipulation
Mouse Events
CSS Transforms
Responsive Design
✨ Future Improvements
Dark mode
More scroll animations
Page transition effects
Smooth scrolling
Loading screen animation

👨‍💻 Author

Made by Anurag 🚀
