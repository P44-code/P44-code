# Hi there, I'm Punam Behera! 👋

### 👨‍💻 Full-Stack Backend Engineer & Tech Community Leader
I am a **BCA student** specializing in high-concurrency backend architectures, real-time event systems, and scalable APIs. As a **Campus Mantri at GeeksforGeeks**, I combine technical implementation with community leadership to bridge the gap between software development and tech mentorship.

---

### 🛠️ Tech Stack & Tools

- **Backend & Event Architectures:** Node.js, Express.js, Socket.IO, RESTful APIs, Multer
- **Databases & Modeling:** MongoDB, Mongoose ODM, SQL, JDBC, Geospatial Filtering
- **Languages:** JavaScript (ES6+), Java
- **Cloud & DevOps:** ImageKit.io CDN, Git, GitHub, Render, Netlify, JWT Authentication

---

### 🚀 Key Projects

#### 🛠️ [SafeArrival](https://github.com) — Real-Time Proximity Match Platform
*Built solo for the Prasunet Hackathon (₹1,00,000 prize track).*
- **Real-Time Mesh:** Implemented scalable, bidirectional event streaming using **Socket.IO** to push customer demands to verified local service workers instantly without polling overhead.
- **Race Condition Prevention:** Eliminated duplicate bookings by engineering an atomic database lock layer via MongoDB `findOneAndUpdate` checking conditional query states (`status: "open"`) under heavy load.
- **Geospatial Processing:** Integrated real-time proximity matching utilizing mathematical Haversine calculations to restrict localized event broadcasting within a strict 15km service provider radius.

#### 🖼️ [ImageKit Media Feed Engine](https://github.com) — Full-Stack CDN Upload Platform
*A lightweight media application processing real-time binary streams and asset distribution.*
- **In-Memory Buffering:** Implemented `multer.memoryStorage()` handling multipart payloads directly in RAM streams to protect disk I/O operations and eliminate server storage overhead.
- **CDN Architecture:** Integrated ImageKit's native SDK engine to transform raw buffers into fast, globally cached CDN image paths instantly (`urlEndpoint`).
- **Dynamic Content Flow:** Developed a responsive feed engine connecting a React.js client interface to a custom Mongoose metadata schema over REST endpoints using Axios.

---

### 📊 GitHub Stats & Velocity
*(These dynamic cards will automatically track your commits as you push code!)*

![Your GitHub Stats](https://vercel.app)
![Top Langs](https://vercel.app)

---

### 🤝 Connect with Me
- **Role Targets:** GitHub Octernships, Open Source Contributions, Backend Internships
- **Community:** Ask me about organizing tech events, DSA prep, or coding bootcamps on campus via GeeksforGeeks!

