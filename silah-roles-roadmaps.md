# Silah Graduation Project – Role-Based Learning Roadmaps

Welcome to the learning and planning document for our graduation project, **Silah**. This file is meant to help us prepare for the development of our system by clearly listing the skills and tools required for each **development role**. The goal is to make sure every team member has a clear path to follow and learns exactly what they need to build Silah successfully.

## Project Roles

Our project is divided into two main technical roles:

- **Frontend Developer**
- **Backend Developer**

Each of these roles will have its own detailed learning roadmap. These roadmaps are **beginner-friendly** and assume no prior knowledge; we’ll start from the basics and grow into advanced project-specific needs.

### What About AI Tasks?

Although our project includes AI features (demand forecasting and semantic search), I decided **not to assign an “AI Engineer” role**. This is because AI-related work will only be needed for a short time during the semester. Instead, some of us will **pause our main roles temporarily** to focus on AI tasks (fine-tuning, testing, and integrating models), and then return to our main roles after that work is done. A separate roadmap will be created for the AI tasks.

## A Note About Choosing Your Role and Learning at Your Own Pace

Please don’t feel any pressure to choose your role right now.

You don’t need to decide whether you want to be a frontend or backend developer yet. One of the reasons we’re making these roadmaps is to help you **explore**, **try things out**, and see what fits you best. You might discover your preference along the way, and that’s completely okay.

Also, keep in mind that **you are not expected to complete every task in these roadmaps**. These learning plans are just a way to prepare during the summer if you want to, not something you _have_ to do.

These learning plans are **not mandatory**. They’re not part of the official graduation project requirements. You’re only expected to work on the graduation project during the semester. But if you want to take the chance to build skills, feel more confident, or try new things; then these roadmaps are here to support you, they are not expectations or obligations.

If you find yourself needing a break, or if something takes longer to understand, or if you’re simply not in the mood to go deep into the material right now; that is completely valid. Any pace you choose is the right one.

I’ll also use **color coding** in the roadmaps to show what’s most important and what’s low-priority or optional, so you can choose what fits your time and energy best.

**Take your time. Explore. Learn. Rest.**

---

## Frontend Development Roadmap

This section is for anyone who wants to take the role of **Frontend Developer** in our graduation project, _Silah_. As frontend devs, our main job is to bring the user interface (UI) to life; the pages, buttons, menus, inputs, and everything users see and interact with on the website.

### Goal of the Frontend Roadmap

By the end of this roadmap, you'll be able to:

- Understand the structure of web pages (HTML)
- Style those pages (CSS)
- Add interactivity (JavaScript)
- Build powerful UIs using React (our chosen frontend framework)
- Apply responsive design and style layouts for both LTR and RTL languages (Arabic & English)
- Collaborate with your teammates using Git and GitHub
- Prepare to work with data and APIs provided by the backend team
- Communicate with backend APIs securely, including understanding how JWT works from the frontend perspective
- Use language files to manage bilingual content and integrate the Google Translate API for dynamic translation when needed
- Implement lazy loading for performance optimization
- Use Tap Payment Gateway API to process online payments
- Build, test, and polish frontend features that are ready to plug into the backend

### How to Use This Roadmap

This is not a strict path. You don’t have to go through everything perfectly or quickly. Move at your own pace, and choose what works for you.

There will be tasks marked with different **priority levels** — high priority (orange), medium (yellow), and optional (blue). Focus first on the important tasks especially if you're short on time.

Don’t worry if you don’t understand the tasks yet! The topics will become clear as you follow tutorials and start writing code.

You can find suggested learning resources (YouTube Videos and Playlists) on our WhatsApp group "مجموعة مشاركة البحوث ونتائجها", and please share the resources you find with us as well!

## Frontend Dev Roadmap

### 1. Learn the Basics of the Web

- 🔶 HTML: Structure of web pages
- 🔶 CSS: Styling your pages
- 🔶 JavaScript: Making things interactive

### 2. Learn Git and GitHub

- 🔶 Git: Local version control

  - What Git is and why we use it
  - Basic commands (init, status, add, commit, log, diff)
  - How to use Git in the terminal of your IDE or text editor of choice
  - How to view commit history and navigate between commits

- 🔶 GitHub: Sharing and collaborating

  - What GitHub is and how it's different from Git
  - How to create and upload (push) a repository
  - How to clone an existing repo to your local machine
  - The concept of remote repositories (origin/main)
  - GitHub's special repository (username.github.io (used for portfolios))
  - `README.md`; writing good documentation
  - Markdown basics (for docs, issues, and comments)
  - `.gitignore`; what it does and when to use it
  - Understand these common terms:
    - Clone
    - Fork
    - Push
    - Pull
    - Pull Request (PR)
    - Merge
  - How to do code reviews on PRs
  - GitHub Issues; tracking tasks, bugs, and feature requests
  - GitHub Projects; organizing work using boards (Kanban-style)
  - GitHub extensions for your IDE/TextEditor (VS Code, IntelliJ, etc.)
  - Understand GitHub Flow; the basic workflow (branch, commit, PR, merge)
  - What is rebase and how it compares to merge
  - What is Git stash and how to use it (save uncommitted changes temporarily)
  - What is Git squash and when to use it (combine multiple commits into one)
  - How to resolve merge conflicts

### 3. Learn React

React is the JavaScript library we’ll use to build the frontend of Silah. It's very popular and used by many big companies like Facebook, Instagram, Netflix, and more. It helps you create dynamic, reusable, and responsive components that update efficiently when the data changes.

What You’ll Learn in This Step:

- 🔶 React Basics

  - What is React and why to use it
  - How React works (JSX, Virtual DOM, Components)

- 🔶 Core Concepts

  - Functional Components
  - Props (passing data between components)
  - State (the concept of storing and updating data in a component)
  - Conditional Rendering (showing UI based on certain conditions)
  - Lists and Keys (handling and displaying multiple items)
  - Hooks (React's way to add logic to functional components)
    - useState (for state)
    - useEffect (for side effects like fetching data)
    - useContext (for global data sharing)
    - useRef (for directly accessing DOM elements or persisting values)

- 🔶 Routing and Navigation

  In React, routing allows your app to have multiple pages (called “routes”) and switch between them without reloading the page. This gives users a smooth experience, like in a native mobile app.

  What to learn:

  - React Router (the most popular routing library for React)
  - Defining routes with `<Route />`
  - Navigating between pages with `<Link />` or `useNavigate()`
  - Route parameters (like `/users/:id`)
  - Nested routes (pages inside pages)

- 🔶 Making API Requests

  In real apps, the frontend often needs to communicate with the backend; to send data, get data, or stay updated in real time. React apps usually use HTTP (like GET or POST) or WebSocket (for real-time updates).

  What to learn:

  - Axios (a library for sending HTTP requests)
  - Sending GET, POST, and other HTTP requests using Axios
  - Handling responses and catching errors
  - Using `async/await` with `try/catch`
  - Creating WebSocket connections using Socket.IO
  - Send messages -the text entered by users- to the backend over a WebSocket

  > **Note:**
  > To practice sending real requests you can use public mock APIs. These give you realistic data and help you get comfortable with requests and responses.
  >
  > Try one of these:
  >
  > - [JSONPlaceholder](https://jsonplaceholder.typicode.com)
  > - [GitHub API](https://api.github.com)
  > - [Fake Store API](https://fakestoreapi.com/)
  > - [Reqres](https://reqres.in/)

- 🔹 Using JSON Server

  JSON Server lets you create a fake REST API locally using a simple JSON file. This is useful for testing your frontend while the real backend is still being built. You’ll be able to test GET, POST, PUT, DELETE requests like a real backend, but with no actual backend logic or database.

- 🟡 Testing with Jest

  Testing helps you make sure your code works and stays reliable, even as your app grows.
  Jest is the most common testing tool for React, it runs your tests and tells you if anything breaks.

  What to learn:

  - **Unit Testing** – test a single component or function in isolation
  - **Integration Testing** – test how components or logic work together
  - **System Testing** – test how the user experiences the app (e.g. simulate clicks and see if the UI behaves correctly)

  > **Note:**
  > You won’t need to write system tests right now because they require a working backend and a fully integrated environment.  
  > The goal is to understand what system testing is and why it’s important, even if you don’t write the code yourself yet.

  ### 4. Advanced & Project-Specific Topics

This step covers **Silah-specific needs** and more advanced frontend skills that help us build a polished, professional app. These are not beginner topics, but they are essential to mastering what we need for our project.

- 🟡 Multilingual Support with Language Files

  - Why we need language files (instead of hardcoding text)
  - Creating language files (e.g. `en.json`, `ar.json`)
  - Loading and switching languages dynamically in React
  - Best practices for translation keys and file structure

- 🟡 Writing CSS for RTL + LTR Support

  Supporting both Arabic and English requires smart styling that works for both directions with minimal duplication.

  - Understanding direction-aware styling (`direction: rtl` / `ltr`)
  - Using logical CSS properties (`margin-inline`, `padding-inline-start`, etc.)
  - Avoiding duplication: how to write once and support both directions

    > There’s a great playlist made by "Elzero Web School" that covers all of this topic: [أفضل طرق عمل موقع متعدد اللغات](https://www.youtube.com/playlist?list=PLDoPjvoNmBAxNQiUCxhjfDM8STo1_Dl8c)

- 🔹 Using Google Translate API

  In some cases (e.g. dynamic user-generated content), we won't use manual translations. Instead, we'll use the Google Translate API to helps us translate content on the fly.

  - How to send text to the API and get translated content
  - Handling async translation and updating UI

- 🔹 Integrating Tap Payment Gateway

  For payments, we’ll use [Tap Payments Gateway](https://tap.company/). The frontend will be responsible for preparing the payment UI and redirecting users.

  - How payment gateways work (for the frontend role only)
  - Redirecting users to Tap’s hosted payment page
  - Handling success/cancel redirects and updating the UI

- 🟡 Authentication (JWT, Cookies, Sessions) (For the Frontend Role Only)

  We’re using JWT in this project, and frontend developers should understand the basics of how auth works in React apps.

  - What is a JWT and how it’s used in communication
  - Where to store the token securely (localStorage vs memory vs httpOnly cookies) (In our project we'll store them in localStorage)
  - Sending tokens with requests (usually via `Authorization` header)
  - Logging out: clearing tokens or sessions
  - When to use sessions or cookies (brief overview only)

  > You’re not responsible for implementing the full auth logic, but you **should know how to handle tokens** if the backend gives them to you.

- 🔹 Lazy Loading in React

  Lazy loading helps make our app faster by **loading only what we need, when we need it**, like splitting routes or components.

  - What is lazy loading and why it matters
  - Using `React.lazy()` and `Suspense` for component-level lazy loading
  - Code splitting with React Router (split pages)
  - Best practices to avoid slow initial loads

- 🔹 Using [Chart.js](https://www.chartjs.org) with React

Chart.js is a powerful and lightweight JavaScript library for creating interactive and beautiful charts and graphs on the web. It supports many types of charts like line, bar, doughnut, pie, and radar charts. In our project, we’ll use it to **visualize supplier profits** and **display AI-based demand forecasts** in a user-friendly way.

- Installing and importing `chart.js` and `react-chartjs-2`
- Understanding the basic chart structure (`data` and `options`)
- Drawing common chart types:
  - Line Chart (for stock demand prediction over time using AI results)
  - Bar Chart (for monthly profits made by a supplier)
- Customizing charts:
  - Styling the appearance (colors, fonts, sizes, gridlines)
  - Adding tooltips and legends

---

## Backend Development Roadmap

This section is for anyone who wants to take the role of **Backend Developer** in our graduation project, _Silah_. As backend devs, our main job is to build the logic that powers the website; handling user accounts, storing data, managing requests, and talking to the database.

### Goal of the Backend Roadmap

By the end of this roadmap, you'll be able to:

- Understand how web servers and APIs work
- Create and structure backend applications using NestJS (our chosen backend framework)
- Use TypeScript to write safe and scalable backend code
- Connect to a database and perform CRUD operations using Prisma ORM
- Handle authentication using JWT (and optionally sessions or cookies)
- Prepare and expose APIs that the frontend team will use
- Learn how to structure backend code for clean, maintainable architecture

### How to Use This Roadmap

This is not a strict path. You don’t have to go through everything perfectly or quickly. Move at your own pace, and choose what works for you.

There will be tasks marked with different **priority levels** — high priority (orange), medium (yellow), and optional (blue). Focus first on the important tasks especially if you're short on time.

Don’t worry if you don’t understand the tasks yet! The topics will become clear as you follow tutorials and start writing code.

You can find suggested learning resources (YouTube Videos and Playlists) on our WhatsApp group "مجموعة مشاركة البحوث ونتائجها", and please share the resources you find with us as well!

## Backend Dev Roadmap

### 1. Learn the Basics of the Web

- 🔶 HTML: Structure of web pages
- 🔶 CSS: Styling your pages
- 🔶 JavaScript: Making things interactive
- 🔶 TypeScript: JavaScript but with types

### 2. Learn Git and GitHub

- 🔶 Git: Local version control

  - What Git is and why we use it
  - Basic commands (init, status, add, commit, log, diff)
  - How to use Git in the terminal of your IDE or text editor of choice
  - How to view commit history and navigate between commits

- 🔶 GitHub: Sharing and collaborating

  - What GitHub is and how it's different from Git
  - How to create and upload (push) a repository
  - How to clone an existing repo to your local machine
  - The concept of remote repositories (origin/main)
  - GitHub's special repository (username.github.io (used for portfolios))
  - `README.md`; writing good documentation
  - Markdown basics (for docs, issues, and comments)
  - `.gitignore`; what it does and when to use it
  - Understand these common terms:
    - Clone
    - Fork
    - Push
    - Pull
    - Pull Request (PR)
    - Merge
  - How to do code reviews on PRs
  - GitHub Issues; tracking tasks, bugs, and feature requests
  - GitHub Projects; organizing work using boards (Kanban-style)
  - GitHub extensions for your IDE/TextEditor (VS Code, IntelliJ, etc.)
  - Understand GitHub Flow; the basic workflow (branch, commit, PR, merge)
  - What is rebase and how it compares to merge
  - What is Git stash and how to use it (save uncommitted changes temporarily)
  - What is Git squash and when to use it (combine multiple commits into one)
  - How to resolve merge conflicts

### 3. Learn NestJS

NestJS is a framework for building efficient and scalable server-side applications using TypeScript. This roadmap guides you through essential and advanced backend topics.

- 🔶 NestJS Fundamentals

  - What is NestJS and how it works
  - Project structure and architecture (controllers, providers, modules)
  - Modules: organizing your application
  - Controllers: handling HTTP routes
  - Services: business logic layer
  - Dependency Injection
  - Decorators: how NestJS uses them
  - Routing and route parameters
  - Middleware and lifecycle hooks
  - Exception filters and global error handling
  - Pipes, Guards, and Interceptors

- 🔶 Working with Prisma

  - PostgreSQL basics (schemas, relations, foreign keys)
  - Setting up Prisma with NestJS
  - Creating models and migrations (`npx prisma migrate dev`)
  - Performing CRUD operations
  - Handling relations and nested writes
  - Managing data using Prisma Client and pgAdmin
  - Seeding the database
  - Error handling and logging
  - Using Prisma middlewares
  - Writing raw SQL queries if needed

- 🔶 Authentication and Authorization

  - Understanding JWT-based authentication
  - Implementing Register/Login with hashed passwords (`bcrypt`)
  - Access vs Refresh Tokens
  - Storing and verifying tokens
  - Role-based access control (RBAC)
  - Using Guards and custom decorators
  - DTOs and Pipes for validation (`class-validator`, `class-transformer`)

- 🔶 Working with WebSockets

  - Creating and handling WebSocket gateways in NestJS
  - Listening to and emitting real-time events

- 🔶 Working with File Uploads

  - Upload images using `@nestjs/platform-express` and Multer
  - Validate file types and size
  - Generate unique file names for uploaded files
  - Upload files directly to Cloudflare R2 using the S3-compatible API
  - Store the resulting file URLs in the PostgreSQL database using Prisma
  - Do not serve static files locally, files are accessed directly via R2 URLs
  - (Optional) Use environment variables to store R2 credentials securely

- 🔶 Testing The Backend

  - Using Postman/Thunder Client for manual testing
  - Setting up Jest for automated testing
    - Unit Testing
    - Integration Testing
    - System Testing

- 🟡 APIs & Documentation

  - RESTful API design principles
  - Creating consistent and versioned API endpoints
  - Using `@nestjs/swagger` to generate OpenAPI docs

### 4. Advanced & Project-Specific Topics

- 🟡 Notifications

  - How to send system messages or updates to users (email, toast, push)

- 🟡 Tap Payments Gateway

  - Preparing and verifying backend payment sessions
  - Handling secure callback responses
  - Understanding the flow of online payments
  - Securely storing Tap API keys using `.env`

- 🔶 Scheduled Tasks (Cron Jobs)

  - Use `@nestjs/schedule` package to define cron jobs
  - Create periodic background jobs (e.g., cleanup, email reminders)
  - Use cron expressions to schedule tasks

- 🔹 Wathq API Integration

  - What it is, how to authenticate, and how to consume the API in NestJS

- 🟡 Error Handling

  - Using filters, interceptors, and custom exceptions

---

## AI Development Roadmap

This section is for anyone who wants to contribute to the **AI-related tasks** in our graduation project, _Silah_. The goal here is to prepare, fine-tune, deploy, and finally integrate our AI models into the working system, so users can benefit from smart features like **semantic search** and **demand forecasting**.

This is not a theoretical AI study. We’re focusing on **practical tasks** to bring real AI functionality into our project.

### Goal of the AI Roadmap

By the end of this roadmap, you'll be able to:

- Understand what each AI model does and how it works
- Fine-tune pre-trained models (LaBSE and Facebook Prophet) using the found datasets
- Deploy these models to a cloud platform (DigitalOcean) so they’re accessible online
- Integrate them into the backend (FastAPI) and connect to the frontend (React)
- Handle requests like:
  - “What’s the expected demand for this product in the coming three months?”
  - “What are some alternative products similar to this one?”

### Our AI Tasks

We have **two main AI features**:

1. **Semantic Search for Alternatives**

   - **Model**: LaBSE (Language-Agnostic BERT Sentence Embedding)
   - **Task**: When a user types something like “towel”, we find products in our database with similar meaning, not just similar text.
   - **Method**: Convert both the search query and product descriptions into embeddings, then use cosine similarity to find the closest matches.

2. **Product Demand Forecasting**
   - **Model**: Facebook Prophet
   - **Task**: Predict how much of a certain product will be needed in the coming three months.
   - **Method**: Fine-tune Prophet on historical stock data provided by suppliers.

### AI Workflow Summary

There are **3 main phases** in the AI work for our project:

1. **Fine-Tuning**  
   We already have pre-trained models, but we will fine-tune them using public datasets to improve accuracy and relevance to our domain.

2. **Deployment**  
   We’ll deploy the models as separate services on DigitalOcean. This way, the backend can send API requests to them just like any external service.

3. **Integration**  
   This is where we connect everything. FastAPI will act as a bridge, sending user inputs to the models and receiving predictions or results. Then, we display those results to the user via our website frontend.

### How to Use This Roadmap

This roadmap is a **temporary guide** just for the AI features we are developing. You don’t need to be an expert in AI to contribute; just follow the steps, and learn by doing.

We’ll also share YouTube tutorials and helpful notes in our WhatsApp group _"مجموعة مشاركة البحوث ونتائجها"_, don’t forget to contribute what you find as well!

## AI Tasks Roadmap

### 1. Introduction to AI and Machine Learning

You don’t need to become an AI researcher, but you should understand machine learning at a practical, high level.

- What is AI vs ML vs Deep Learning
- Types of ML: Supervised vs Unsupervised vs Reinforcement Learning
- What is a model: inputs, outputs, training, and inference
- Training vs Fine-tuning vs Transfer learning
- Pre-trained models and how to use them
- What is an embedding?
- What is inference time? Why we separate training from serving

### 2. Python for AI

We use Python to train, serve, and deploy models using FastAPI.

- Python syntax (variables, loops, functions, classes)
- NumPy and Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Installing libraries with `pip`
- Using Jupyter Notebooks
- File I/O and JSON handling

### 3. Semantic Search using LaBSE

LaBSE (Language-agnostic BERT Sentence Embedding) maps sentences into a shared vector space. We use it to implement semantic search for product alternatives.

- Sentence embeddings and how they work
- Cosine similarity
- Using HuggingFace Transformers or `sentence-transformers`
- How to compute and save embeddings
- Comparing user input with precomputed data

### 4. Demand Forecasting using Facebook Prophet

Prophet forecasts future product demand from historical data. We use it to help the business understand what to stock.

- Time series data: trend, seasonality, holidays
- Prophet's input format: `ds`, `y`
- Training, plotting, and evaluating a forecast

### 5. Serving Models with FastAPI

We will expose both LaBSE and Prophet as REST APIs using FastAPI.

- What is FastAPI and why it’s used
- Creating routes and endpoints
- Accepting JSON input and returning JSON output
- Loading models once at startup
- Error handling and validation

### 6. Deploying the AI Models

We will make the AI models publicly accessible by deploying them to a cloud VM (DigitalOcean).

- What is a VM/Droplet
- Installing Python and dependencies
- Running FastAPI with `uvicorn`, `gunicorn`
- Running services in the background with `pm2` or `systemd`
- Basic server security (SSH keys, disable root)

### 7. Frontend Integration

Once deployed, the AI services will be used by the frontend.

- Semantic Search API:
  - Frontend sends a query to FastAPI endpoint → gets most similar product → shows results in UI
- Prophet Forecast API:
  - Frontend sends product ID to FastAPI endpoint → gets 90 days forecast → plots it using Chart.js

---

May Allah put barakah in our efforts and make it beneficial for the Ummah.
