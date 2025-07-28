#Analog Clock
A modern, real-time analog clock built with HTML, CSS, and JavaScript. This project demonstrates DOM manipulation, CSS variables, and dynamic rotation using JavaScript's Date() object.

#Preview
<img width="265" height="248" alt="Screenshot png" src="https://github.com/user-attachments/assets/b885f9fa-3eac-4618-997a-d9afae0ecdb9" />

#Features
Real-time analog clock synced with the system time
Smooth rotation of hour, minute, and second hands
Styled with radial gradients, shadows, and a modern glassy effect
Fully responsive and visually engaging

#Technologies Used
 HTML5 – Structure and clock elements
 CSS3 – Styling, gradients, and transformations
 JavaScript(ES6) – Logic to update clock hands every second

#Project Structure
*index.html
*style.css 
*script.js 

#How It Works
The clock uses CSS custom properties (--rotate) to dynamically rotate each hand based on the current system time.
const seconds = date.getSeconds() / 60;
     const minutes = (seconds + date.getMinutes()) / 60;
      const hours = (minutes + date.getHours()) / 12;
      
Then sets the rotation:
element.style.setProperty('--rotate', rotation * 360);

#Acknowledgments
Inspired by traditional wall clocks, brought to life with clean modern CSS and JavaScript techniques.
