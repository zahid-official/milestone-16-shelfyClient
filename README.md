<div align="center">

<img src="https://cdn-icons-png.flaticon.com/512/2702/2702134.png" alt="Shelfy Logo" width="60" />

# Shelfy - Library Management System

A comprehensive, user-friendly web application for streamlined library operations built with React, TypeScript and modern web technologies.

[![Backend Repo](https://img.shields.io/badge/Backend-Repository-4CAF50?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://github.com/zahid-official/milestone-16-shelfyServer)
[![GitHub Repo](https://img.shields.io/badge/Frontend-Repository-181717?style=for-the-badge&logo=github)](https://github.com/zahid-official/milestone-16-shelfyClient)
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux Toolkit" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />

</div>

<br/>

## 🔍 Frontend Overview

> **Shelfy** is a production-ready, full-featured web application that serves as the visual interface for the Shelfy ecosystem. It provides an intuitive, responsive experience for browsing books, managing inventory, and tracking borrow activities.

This repository focuses exclusively on the **Client-Side UI**, consuming the RESTful API from the [Shelfy Backend Server](https://github.com/zahid-official/milestone-16-shelfyServer).

<br/>

## ✨ Key Features

### 📚 Book Management

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Book Catalog</b></td><td>Browse all books with advanced sorting and genre filtering</td></tr>
<tr><td><b>CRUD Operations</b></td><td>Create, read, update and delete book records with real-time feedback</td></tr>
<tr><td><b>Rich Metadata</b></td><td>Title, Author, Genre, ISBN, Description and copy management</td></tr>
<tr><td><b>Availability Tracking</b></td><td>Automatic status updates based on available copies</td></tr>
</tbody>
</table>

### 🔄 Borrowing System

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Streamlined Checkout</b></td><td>Simple, intuitive book borrowing process with form validation</td></tr>
<tr><td><b>Due Date Picker</b></td><td>Flexible date selection with future-date enforcement via React Day Picker</td></tr>
<tr><td><b>Inventory Sync</b></td><td>Real-time availability updates reflected immediately across the UI</td></tr>
<tr><td><b>Borrow Summary</b></td><td>Aggregated dashboard showing total borrow quantities per book</td></tr>
</tbody>
</table>

### 🎨 UI & Developer Experience

<table align="center">
<thead>
<tr><th align="left">Feature</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Dark / Light Mode</b></td><td>Theme switching powered by next-themes with zero flash</td></tr>
<tr><td><b>Toast Notifications</b></td><td>Elegant success and error feedback via Sonner</td></tr>
<tr><td><b>Accessible Components</b></td><td>Built on Radix UI primitives for WCAG-compliant interactions</td></tr>
<tr><td><b>Responsive Design</b></td><td>Optimized layout for desktop, tablet and mobile devices</td></tr>
</tbody>
</table>

<br/>

## 🛠️ Tech Stack

<table align="center">
<thead>
<tr><th align="left">Technology</th><th align="center">Version</th><th align="left">Purpose</th></tr>
</thead>
<tbody>
<tr><td><b>React</b></td><td align="center"><code>^19.1.0</code></td><td>Core UI library with concurrent features</td></tr>
<tr><td><b>TypeScript</b></td><td align="center"><code>~5.8.3</code></td><td>Type-safe development experience</td></tr>
<tr><td><b>Vite</b></td><td align="center"><code>^7.0.4</code></td><td>Lightning-fast build tool and dev server</td></tr>
<tr><td><b>Redux Toolkit</b></td><td align="center"><code>^2.8.2</code></td><td>Global state management</td></tr>
<tr><td><b>RTK Query</b></td><td align="center"><code>^2.8.2</code></td><td>Efficient API data fetching and caching</td></tr>
<tr><td><b>React Router</b></td><td align="center"><code>^7.7.1</code></td><td>Client-side routing</td></tr>
<tr><td><b>Tailwind CSS</b></td><td align="center"><code>^4.1.11</code></td><td>Utility-first CSS framework</td></tr>
<tr><td><b>Radix UI</b></td><td align="center"><code>^1.4.3</code></td><td>Accessible, unstyled component primitives</td></tr>
<tr><td><b>React Hook Form</b></td><td align="center"><code>^7.62.0</code></td><td>Performant form state management</td></tr>
<tr><td><b>Zod</b></td><td align="center"><code>^4.0.14</code></td><td>Runtime schema validation</td></tr>
<tr><td><b>Lucide React</b></td><td align="center"><code>^0.535.0</code></td><td>Consistent, beautiful icon library</td></tr>
<tr><td><b>React Day Picker</b></td><td align="center"><code>^9.8.1</code></td><td>Flexible date picker component</td></tr>
<tr><td><b>Sonner</b></td><td align="center"><code>^2.0.7</code></td><td>Elegant toast notification system</td></tr>
<tr><td><b>next-themes</b></td><td align="center"><code>^0.4.6</code></td><td>Dark/light mode theme management</td></tr>
<tr><td><b>date-fns</b></td><td align="center"><code>^4.1.0</code></td><td>Modern date utility library</td></tr>
<tr><td><b>clsx / tailwind-merge</b></td><td align="center"><code>^2.1.1</code></td><td>Conditional class name utilities</td></tr>
</tbody>
</table>

<br/>

## 🏗️ Architecture

<div>
<pre>
                           ┌───────────────────────────────────────────────────┐
                           │                    Browser Client                 │
                           │              React 19 + TypeScript + Vite         │
                           └──────────────────────┬────────────────────────────┘
                                                │
                           ┌──────────────────────▼────────────────────────────┐
                           │                  React Router v7                  │
                           │       /books   /create-book   /borrow/:id         │
                           └───────────┬───────────────────────────────┬───────┘
                                       │                               │
                           ┌───────────▼──────────┐       ┌────────────▼────────────┐
                           │   Page Components    │       │   Redux Store           │
                           │  (Layouts/Pages)     │       │   RTK Query Slices      │
                           └───────────┬──────────┘       └────────────┬────────────┘
                                       │                               │
                           ┌───────────▼───────────────────────────────▼───────────┐
                           │              Shared Components (Radix UI /            │
                           │              Lucide Icons / Tailwind CSS)             │
                           └────────────────────────────┬──────────────────────────┘
                                                      │ HTTP (RTK Query)
                           ┌────────────────────────────▼──────────────────────────┐
                           │            Shelfy Backend REST API                    │
                           │         Node.js · Express · MongoDB                   │
                           └───────────────────────────────────────────────────────┘
</pre>
</div>

<br/>

## 📂 Project Structure

```
milestone-16-client/
├── src/
│   ├── components/         # Reusable UI components (buttons, modals, tables)
│   ├── hooks/              # Custom React hooks
│   ├── layouts/            # Page layout wrappers
│   ├── lib/                # Utility helpers (cn, formatters)
│   ├── pages/              # Route-based page components
│   │   ├── home/           # Landing / dashboard page
│   │   ├── allBooks/       # Book catalog with filter & sort
│   │   ├── addBook/        # Add new book form
│   │   ├── borrowSummary/  # Aggregated borrow analytics
│   │   └── documentation/  # API documentation page
│   ├── providers/          # Theme & Redux providers
│   ├── redux/              # Redux store & RTK Query API slices
│   ├── routes/             # Route definitions
│   ├── schema/             # Zod validation schemas
│   ├── styles/             # Global CSS and Tailwind config
│   ├── types/              # TypeScript type definitions
│   ├── main.tsx            # App entry point
│   └── vite-env.d.ts
├── index.html
├── package.json
├── vite.config.ts
└── README.md
```

<br/>

## 🚀 Getting Started

### Prerequisites

<table align="center">
<thead>
<tr><th align="left">Requirement</th><th align="left">Details</th></tr>
</thead>
<tbody>
<tr><td><b>Node.js</b></td><td>v18 or higher</td></tr>
<tr><td><b>Backend Server</b></td><td><a href="https://github.com/zahid-official/milestone-16-shelfyServer">Shelfy Backend</a> running on port 3000</td></tr>
<tr><td><b>Package Manager</b></td><td>npm or yarn</td></tr>
</tbody>
</table>

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/zahid-official/milestone-16-shelfyClient.git
   cd milestone-16-client
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Configure environment variables**

   Create a `.env.local` file in the root directory:

   ```env
   VITE_API_BASE_URL=http://localhost:3000/api
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```
   The app will open at `http://localhost:5173`

<br/>

## 🔑 Environment Variables

<table align="center">
<thead>
<tr><th align="left">Variable</th><th align="left">Description</th><th align="center">Required</th></tr>
</thead>
<tbody>
<tr><td><code>VITE_API_BASE_URL</code></td><td>Shelfy Backend API base URL</td><td align="center">Yes</td></tr>
</tbody>
</table>

<br/>

## 📜 Available Scripts

<table align="center">
<thead>
<tr><th align="left">Script</th><th align="left">Command</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><b>Development</b></td><td><code>npm run dev</code></td><td>Start Vite dev server with HMR</td></tr>
<tr><td><b>Build</b></td><td><code>npm run build</code></td><td>Type-check and build for production</td></tr>
<tr><td><b>Preview</b></td><td><code>npm run preview</code></td><td>Preview the production build locally</td></tr>
<tr><td><b>Lint</b></td><td><code>npm run lint</code></td><td>Run ESLint across the codebase</td></tr>
</tbody>
</table>

<br/>

## ⚙️ Application Routes

<table align="center">
<thead>
<tr><th align="left">Route</th><th align="left">Page</th><th align="left">Description</th></tr>
</thead>
<tbody>
<tr><td><code>/</code></td><td>Home</td><td>Landing page and dashboard overview</td></tr>
<tr><td><code>/books</code></td><td>All Books</td><td>Browse, filter, sort and manage the catalog</td></tr>
<tr><td><code>/books/:id</code></td><td>Book Details</td><td>Full book information and quick actions</td></tr>
<tr><td><code>/create-book</code></td><td>Add Book</td><td>Form to create a new book record</td></tr>
<tr><td><code>/edit-book/:id</code></td><td>Edit Book</td><td>Pre-filled form to update book details</td></tr>
<tr><td><code>/borrow/:bookId</code></td><td>Borrow Book</td><td>Quantity selection and due date picker</td></tr>
<tr><td><code>/borrow-summary</code></td><td>Borrow Summary</td><td>Aggregated borrowing analytics dashboard</td></tr>
<tr><td><code>/documentation</code></td><td>Documentation</td><td>API and usage documentation</td></tr>
</tbody>
</table>

<br/>

## 🌟 How It Works

**Data Flow:**

<div>
<pre>
                                 User Interaction (e.g. Borrow a Book)
                                                   │
                                                   ▼
                              React Component dispatches RTK Query mutation
                                                   │
                                                   ▼
                               RTK Query sends POST /api/borrow to backend
                                                    │
                                             ┌──────┴───────┐
                                             │              │
                                             ▼              ▼
                                          Success?       Error?
                                             │              │
                                             ▼              ▼
                                    Invalidates cache  Sonner toast
                                    Auto-refetches     shows error
                                    book list data     message
                                             │
                                             ▼
                                   UI updates instantly with fresh data
</pre>
</div>

1. **User triggers action** — clicks a button or submits a form
2. **React Hook Form validates** — Zod schema runs against form values client-side
3. **RTK Query fires request** — mutation or query sent to the Shelfy backend API
4. **Cache invalidated on success** — related queries auto-refetch for fresh data
5. **Sonner notifies user** — toast confirms success or surfaces error message
6. **UI reflects new state** — components re-render with updated Redux store data

<br/>

<div align="center">

<img src="https://github.com/zahid-official.png" alt="Zahid Official" width="80" style="border-radius: 50%;" />

<h3>Zahid Official</h3>
<p><b>Web Developer | Tech Enthusiast</b></p>

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zahid-web)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zahid.official8@gmail.com)

<p>Transforming complex requirements into fluid, high-performance digital realities.</p>

</div>

<br/>

## 🤝 Contributing

```bash
# 1. Fork the repository on GitHub

# 2. Clone your fork
git clone https://github.com/your-username/milestone-16-client.git

# 3. Create a feature branch
git checkout -b feature/your-feature-name

# 4. Commit your changes
git commit -m "feat: add your feature description"

# 5. Push to your fork
git push origin feature/your-feature-name

# 6. Open a Pull Request on GitHub
```


<div align="center">
<p><b>Shelfy</b> - <i>Redefining library efficiency through seamless digital innovation.</i></p>
</div>
