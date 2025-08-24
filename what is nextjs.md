# 📘 What is Next.js?

**Next.js** is a **React-based web framework** developed by **Vercel**. It enables **server-side rendering** (SSR), **static site generation** (SSG), and **hybrid** rendering, allowing developers to build **fast, SEO-friendly**, and **scalable** web applications.

---

## 🧠 Key Concepts

### 1. React Framework
- Built on top of **React.js**.
- Adds extra features and optimizations that React alone doesn’t provide.

### 2. Routing

- Next.js supports **two routing systems**:
  - **Pages Router** (`pages/` directory)
  - **App Router** (`app/` directory – introduced in Next.js 13+, now recommended)

#### Pages Router
- Uses **file-based routing** in the `pages/` directory.
- Each file becomes a route.
  - Example: `pages/about.js` → `/about`

#### App Router (Recommended)
- Uses the `app/` directory for **React Server Components** and **nested layouts**.
- Supports advanced routing features:
  - **Nested routes** with layout and templates
  - **Dynamic routes**: `app/blog/[slug]/page.tsx` → `/blog/my-article`
  - **Catch-all routes**: `[...slug]`
  - **Intercepting routes**: `(.)`, `(..)`, `(...)` syntax
- Enables **streaming**, **partial rendering**, and **server actions**

> ✅ As of Next.js 15, the **App Router is fully stable** and recommended for new projects.


### 3. Rendering Methods
- **Static Site Generation (SSG)** – `getStaticProps()`
- **Server-Side Rendering (SSR)** – `getServerSideProps()`
- **Client-Side Rendering (CSR)** – default React behavior
- **Incremental Static Regeneration (ISR)** – update static content without a full rebuild

### 4. API Routes
- Backend code using `pages/api/` directory.
- Easily build APIs alongside frontend.

### 5. Image Optimization
- Built-in `next/image` component for fast, responsive images.

### 6. Performance Optimizations
- Automatic code splitting.
- Lazy loading.
- Prefetching.

### 7. Built-in CSS & Styling
- Supports:
  - CSS Modules
  - Global CSS
  - Sass/SCSS
  - Tailwind CSS
  - Styled-components

### 8. Middleware (from v12+)
- Add logic to run before a request is completed (e.g., auth, redirects).

### 9. App Directory (from v13+)
- New way to build apps using **Server Components**.
- Allows layout nesting and advanced data fetching.

---

## ✅ Benefits of Next.js

- ⚡ **Fast Performance**
- 🌐 **SEO-Friendly** (SSR/SSG support)
- 🔌 **Full-Stack Capabilities**
- 🔧 **Developer Experience**
- 📱 **Optimized Images and Fonts**

---

## 🛠 Use Cases

- Blogs & content-driven sites
- E-commerce platforms
- Marketing websites
- SaaS dashboards
- Portfolios

---

