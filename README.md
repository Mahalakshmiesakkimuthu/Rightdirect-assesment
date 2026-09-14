# RightDirect Services Page – Technical Assessment

A responsive recreation of the RightDirect Services page, built as part of a technical assessment.

The project uses **Astro** for the frontend and **Sanity CMS** for managing dynamic page content.

## 🚀 Live Demo

https://rightdirect-assesment-p1lo.vercel.app/

## 📌 Project Overview

This project recreates the RightDirect Services page with a focus on:

* Responsive design
* Reusable Astro components
* Dynamic content using Sanity CMS
* Editable text, images, and CTA content
* Desktop, tablet, and mobile layouts
* Accessibility-friendly structure
* SEO metadata

## 🛠️ Technologies Used

* **Astro** – Frontend framework
* **Sanity CMS** – Headless content management
* **JavaScript**
* **HTML**
* **CSS**
* **Vercel** – Deployment
* **Git & GitHub** – Version control

## ✨ Features

### Dynamic CMS Content

Page content is managed through Sanity CMS instead of being hardcoded directly into the components.

Content such as:

* Hero text
* Section headings
* Descriptions
* Images
* CTA buttons
* Work cards
* Approach cards
* Footer content
* SEO title and description

can be updated through Sanity Studio.

### Responsive Design

The page is designed to work across:

* Desktop
* Tablet
* Mobile

### Reusable Components

The page is divided into reusable Astro components, including:

* Header
* Hero
* Approach
* Work
* Footer

This makes the project easier to maintain and update.

## 📂 Project Structure

```text
rightdirect-assessment/
│
├── public/
│   └── images/
│
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Approach.astro
│   │   ├── Work.astro
│   │   └── Footer.astro
│   │
│   ├── lib/
│   │   └── sanity.js
│   │
│   └── pages/
│       └── index.astro
│
├── package.json
└── astro.config.mjs
```

## 🧩 Sanity CMS

A separate Sanity Studio project is used to manage the website content.

The Astro frontend fetches content from Sanity and renders it dynamically.

This allows content to be updated through Sanity Studio without directly modifying the frontend code.

## 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/Mahalakshmiesakkimuthu/Rightdirect-assesment.git
```

Move into the project:

```bash
cd Rightdirect-assesment
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The project will be available at the local development URL shown in the terminal.

## 📱 Responsive Testing

The page was tested across different screen sizes using browser responsive/device mode.

The layout adapts navigation, sections, cards, spacing, typography, and images for smaller screens.

## 🌐 Deployment

The frontend is deployed using **Vercel**.

Sanity CMS is used as the content source for the deployed website.

## 👩‍💻 Author

**Mahalakshmi**

Frontend Developer | MERN Enthusiast

**GitHub Repository:**
https://github.com/Mahalakshmiesakkimuthu/Rightdirect-assesment
