<div align="center">
    <a href="" target="_blank">
      <img src="preview.webp" alt="Project Banner">
    </a>
  <h3 align="center">Docker 🐳 Templates</h3>
</div>

##  <br /> 📋 <a name="table">Table of Contents</a>

- ✨ [Introduction](#introduction)
- ⚙️ [Tech Stack](#tech-stack)
- 📝 [Features](#features)
- 🚀 [Quick Start](#quick-start)

##  <br /> <a name="introduction">✨ Introduction</a>

**[EN]** Examples of containerizing frontend, backend, and database applications built with various tech stacks such as React, Vue, Svelte, and Vite projects. This includes containerization of complete full-stack applications, like MERN setups and popular Monorepo full-stack applications using Next.js.

**[FR]** Exemples de conteneurisation d'applications frontend, backend et de base de données construites avec des stacks technologiques variées telles que React, Vue, Svelte et les projets Vite. Également, des exemples de conteneurisation d'applications full-stack complètes, comme les configurations MERN et les applications full-stack Monorepo populaires utilisant Next.js.

##  <br /> <a name="tech-stack">⚙️ Tech Stack</a>

- **Docker** is a platform that automates the deployment of applications inside lightweight, portable containers. It provides consistent environments for development, testing, and production, allowing developers to package applications and their dependencies together, ensuring they run seamlessly across different systems.

- **React** is a popular JavaScript library for building user interfaces, particularly single-page applications where data changes over time. React's component-based architecture allows developers to create reusable UI components, making development more efficient and the codebase easier to maintain. 

- **Next.js** is a React framework known for its server-side rendering (SSR) and static site generation (SSG) capabilities, enhancing performance and SEO for web applications. It offers features like automatic code splitting, API routes for server-side logic, and a plugin system for extensibility.

- **MongoDB** is a NoSQL database system known for its flexibility and scalability, ideal for handling large volumes of unstructured or semi-structured data. It stores data in JSON-like documents, making it easy to integrate with modern applications. MongoDB's features include powerful querying capabilities, automatic sharding for horizontal scaling, flexible data models, and support for distributed transactions in recent versions.

- **Node.js** is a JavaScript runtime built on Chrome's V8 engine that enables server-side scripting, allowing developers to build scalable network applications. It is known for its non-blocking, event-driven architecture, which ensures high performance and efficiency for handling multiple concurrent connections.

- **Express.js** is a minimalist web framework for Node.js, designed to build web applications and APIs. It offers robust features like routing, middleware support, and templating, making it a popular choice for developing server-side applications with a clean and organized code structure.

- **Vite** is a modern frontend build tool known for fast ES Module imports, efficient bundling, and quick development server startup times. It supports frameworks like Vue.js and React, optimizing workflow and performance compared to traditional bundlers.

- **Tailwind** is a utility-first CSS framework that speeds up UI development by providing a set of pre-built utility classes. It allows developers to quickly build custom designs without writing traditional CSS, promoting rapid prototyping and design consistency.



## <br/> <a name="features">📝 Features</a>

👉 **Fundamentals of Docker**: Understand the fundamentals of Docker, its purpose, and advantages.

👉 **Managing Images and Containers with Docker Compose**: Explore Docker Compose for orchestrating multiple images and containers efficiently.

👉 **Latest Docker Features**: Learn new features such as docker init, docker scout, and docker compose watch for enhanced development workflows.

👉 **Working with Volumes**: Learn how to use volumes for persistent data management in Docker containers

👉 **Port Mapping with Network**: Implement port mapping using Docker's networking capabilities

👉 **Dockerizing React Applications with Vite**: Step-by-step guide on Dockerizing React applications built with Vite.

👉 **Dockerizing Vite Applications (Vue or Svelte)**: Extend the knowledge to Dockerizing Vite applications, supporting Vue or Svelte frameworks.

👉 **Dockerizing Full Stack Applications**: Dockerize a complete MERN stack application, covering frontend, backend, and database.

👉 **Dockerizing Monorepo Full Stack Applications (Next.js 14+)**: Explore Dockerizing Monorepo full-stack applications using the latest features of Next.js (version 14 and above).

👉 **Publishing Docker Images**: Learn the steps to publish Docker images, making your applications accessible to a broader audience.

## <br /> <a name="quick-start">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

<br/>**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

<br/>**Cloning the Repository**

```bash
git clone {git remote URL}
```

<br/>**Installation**

Let's install the project dependencies, from your terminal, run:

```bash
npm install
# or
yarn install
```

<br/>**Set Up Environment Variables**

For a few specific applications, we require environment variables. I've included a sample .env.example file for these essential projects. However, one crucial element needed for these projects is:

```env
#MongoDB
DB_URL=
```
For full stack applications, we'll be using MongoDB as a database. So do create an account on [MongoDB Atlas](https://www.mongodb.com/) as well as 
install [MongoDB Compass](https://www.mongodb.com/products/tools/compass) for creating local database instance for the project. 


<br/>**Running the Project**

Installation will take a minute or two, but once that's done, you should be able to run the following command:

```bash
# (Depending on the project)
npm run dev
# or
npm start
```

Open [`http://localhost:3000`](http://localhost:3000) in your browser to view the project.