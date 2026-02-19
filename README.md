<div align="center">
  <h1>Phys&Math Education Platform</h1>
  <p><strong>A high-performance educational ecosystem for advanced Mathematics and Physics</strong></p>
  <p><em>Engineered for scalability: from custom architectural planning to production-ready deployment</em></p>
</div>

<hr />

<div align="center">
	<img src="./media/demo1.gif" 
			 alt="Platform Demo" 
			 width="100%" 
			 style="max-width: 800px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);"/>
</div>

## 🛠 Engineering Stack

### Frontend & Core Logic
* **Framework**: Next.js 15 (App Router) — utilizing SSR, CSR, and SSG for optimal performance and SEO.
* **Language**: TypeScript (Strict mode) for robust, type-safe development.
* **Styling**: TailwindCSS & SASS/SCSS for modular UI architecture.
* **State Management**: Optimized React Hooks workflow with middleware-based routing.

### Backend & Data Layers
* **Runtime**: Node.js with Express.js.
* **Database**: PostgreSQL with Prisma ORM for type-safe queries.
* **Caching & Sessions**: Redis-backed session management and data caching.
* **Communication**: Socket.IO for real-time bidirectional messaging and live updates.
* **Security**: JWT-based authentication (Access/Refresh tokens) with secure, encrypted cookies.

<div align="center">
	<img src="./media/demo2.gif" 
			 alt="User Interface Demo" 
			 width="90%" 
			 style="max-width: 800px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);"/>
</div>

## 📚 Core Functionality

### 🧠 Algorithmic Task Generation
The platform features deep integration with the **Math Tasks Generator** module.
* **Dynamic Content**: Automated generation of mathematical problems based on predefined algorithmic logic.
* **Adaptive Learning**: Intelligent task distribution categorized by grades (5-9) and national exam standards (NMT/ZNO).
* **Automated Evaluation**: Real-time checking system with error analysis and personalized improvement recommendations.

### 🔐 Enterprise-Grade Security
* Multi-tier authentication system with unique access code registration.
* Secure password recovery pipelines via Nodemailer.
* Robust middleware layers for granular access control (Student vs. Admin).

<div align="center">
	<img src="./media/demo3.gif" 
			 alt="Educational Process Demo" 
			 width="90%" 
			 style="max-width: 800px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);"/>
</div>

## 🏗️ System Architecture & Infrastructure

### Infrastructure & DevOps
* **Environment**: VPS (Ubuntu) managed via Nginx (Reverse Proxy & SSL Termination).
* **Process Management**: PM2 for seamless zero-downtime deployments.
* **Security**: Enforced SSL/TLS certificates and hardened security headers.
* **Observability**: Centralized logging via Winston (monitoring requests, errors, and system health).

### Modular Backend
Built with a **Services/Controllers** pattern to ensure modularity. Prisma ORM ensures the database schema is always synchronized with the application logic, while **Redis** offloads the primary PostgreSQL database for high-frequency session verification.

<hr />

<div align="center">
	<img src="./media/demo4.gif" 
			 alt="Admin Panel Demo" 
			 width="90%" 
			 style="max-width: 800px; border-radius: 10px; box-shadow: 0 5px 15px rgba(0,0,0,0.1);"/>
</div>

<div align="center">
  <h3>🎯 Engineering Values</h3>
  <p><b>Scalability</b>: Built to handle increasing content volumes | <b>Reliability</b>: Fault-tolerant production environment | <b>Clean Code</b>: Maintainable modular codebase</p>

  <br />

  <h3>👨‍💻 Developer</h3>
  <p><strong>Artem Zhyto</strong></p>
  <p><a href="https://github.com/ArtemZhyto">GitHub Profile</a></p>

  <br />

  <p><strong>© 2026 — Built with precision and logic.</strong></p>
</div>
