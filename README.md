# airbnb-clone-project
## Overview
This project is a simplified clone of Airbnb designed to help me practice building full-stack web applications.

## Goals
- Understand how to structure a large-scale web app.
- Practice backend and frontend integration.
- Learn authentication, listing management, and responsive UI.

## Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express
- Database: MongoDB
- Deployment: Vercel / Render

## UI/UX Design Planning

###  Design Goals
The goal of the UI/UX design is to create an intuitive, visually appealing, and responsive interface that mirrors the simplicity and usability of Airbnb. The design will focus on ease of navigation, clarity of information, and a smooth booking flow for users.

Key design objectives:
- Provide a clean and consistent layout across all pages.
- Ensure mobile responsiveness for various screen sizes.
- Optimize user interaction with minimal clicks to complete actions.
- Use clear visual hierarchy and intuitive icons for better usability.

---

###  Key Features to Implement
- **Search and Filter System:** Allow users to find properties by location, price, and availability.  
- **Interactive Property Cards:** Show images, prices, and basic property info at a glance.  
- **Booking Flow:** Enable a seamless transition from browsing to checkout.  
- **Responsive Navigation Bar:** Provides quick access to listings, bookings, and profile pages.  
- **Visual Consistency:** Apply the same color palette, typography, and component styles throughout.  

---

###  Primary Pages Overview

| Page Name | Description | Key Elements |
|------------|--------------|---------------|
| **Property Listing View** | Displays all available listings in a grid or list format. Users can browse, search, and filter results. | - Search bar<br>- Filter options (price, location, dates)<br>- Property cards with images and prices |
| **Listing Detailed View** | Shows comprehensive details of a selected property. | - Property gallery<br>- Host info and amenities<br>- Reviews section<br>- “Book Now” button |
| **Simple Checkout View** | Allows users to confirm their booking details and make payment. | - Booking summary<br>- Payment form<br>- Confirmation button and success message |

###  Figma Design Exploration

####  Color Styles
The design uses a modern, minimal color palette inspired by Airbnb’s clean aesthetic:

- **Primary Color:** `#FF385C` – Main accent color for buttons and highlights.  
- **Secondary Color:** `#222222` – Dark text and headings.  
- **Background Color:** `#FFFFFF` – Clean white background for readability.  
- **Gray Tones:** `#717171`, `#EBEBEB` – Used for subtle borders, text, and hover states.  
- **Success/Confirmation Color:** `#00A699` – For positive actions or messages.

---

####  Typography
The project uses simple and consistent typography for readability and brand coherence.

| Type | Font Family | Font Weight | Font Size |
|------|--------------|--------------|------------|
| **Headings (H1, H2)** | `Inter` or `Poppins` | 600–700 (Bold/Semi-bold) | 24px–36px |
| **Body Text** | `Inter` or `Poppins` | 400 (Regular) | 14px–16px |
| **Captions / Labels** | `Inter` | 500 (Medium) | 12px |

> *Typography ensures visual hierarchy and consistency across all pages.*

---

####  Importance of Identifying Design Properties
Understanding and documenting design properties such as **color styles**, **typography**, and **component spacing** is essential when translating a mockup from Figma to code.  

- It ensures **visual consistency** throughout the application.  
- Helps developers maintain **brand identity** without guessing design values.  
- Makes collaboration between designers and developers more efficient.  
- Simplifies updates and scalability — if a design changes in Figma, developers can adjust styles quickly.

## Project Roles and Responsibilities

A successful software project relies on clear role definition and collaboration across different team members. Below are the key roles and their responsibilities for the Airbnb Clone Project.

| Role | Responsibilities | Contribution to Project Success |
|------|-------------------|---------------------------------|
| **Project Manager (PM)** | - Oversees project planning, scheduling, and progress tracking.<br>- Manages communication between all stakeholders.<br>- Ensures the project stays within scope, budget, and timeline. | Keeps the project organized, aligns the team’s work with goals, and ensures deadlines are met efficiently. |
| **Product Owner (PO)** | - Defines the product vision and roadmap.<br>- Prioritizes features and maintains the product backlog.<br>- Acts as the voice of the customer. | Ensures that development aligns with user needs and business objectives. |
| **Scrum Master** | - Facilitates Scrum ceremonies (stand-ups, sprints, retrospectives).<br>- Removes blockers for the team.<br>- Encourages agile best practices. | Helps the team stay productive and ensures smooth communication within agile processes. |
| **Frontend Developers** | - Implement the user interface based on Figma designs.<br>- Build responsive and accessible components using React and Tailwind CSS.<br>- Integrate frontend with backend APIs. | Bring the UI/UX design to life and ensure users have a smooth, visually appealing experience. |
| **Backend Developers** | - Develop RESTful APIs and manage database operations.<br>- Handle authentication, data validation, and business logic.<br>- Ensure security and scalability. | Provide the logic and data handling that make the application functional and reliable. |
| **Designers (UI/UX)** | - Create wireframes, mockups, and prototypes in Figma.<br>- Define color palettes, typography, and overall design system.<br>- Conduct usability testing. | Enhance usability, ensure visual consistency, and improve the overall user experience. |
| **QA/Testers** | - Test all features for bugs, performance issues, and UI/UX consistency.<br>- Perform manual and automated testing.<br>- Verify that requirements are met. | Maintain software quality and ensure the app is stable and user-ready before deployment. |
| **DevOps Engineers** | - Manage deployment pipelines and version control.<br>- Set up CI/CD processes for automated builds and testing.<br>- Monitor performance and handle cloud infrastructure. | Enable continuous integration, deployment, and reliable server operations. |

---


## UI Component Patterns

The Airbnb Clone project will use a set of reusable, modular UI components to ensure design consistency, maintainability, and scalability across the entire application. Below are the planned components and their purposes.

| Component | Description | Key Features |
|------------|--------------|---------------|
| **Navbar** | The navigation bar displayed at the top of every page. It helps users quickly access different sections of the platform. | - Includes logo and brand name.<br>- Navigation links (Home, Listings, Bookings, Profile).<br>- Responsive hamburger menu for mobile screens.<br>- Sticky positioning for easy access. |
| **Property Card** | A compact card used to display summarized property information within the listings page. | - Property image carousel or thumbnail.<br>- Property title and short description.<br>- Price per night and location.<br>- "View Details" button or clickable link. |
| **Footer** | The footer appears at the bottom of all pages, providing helpful links and contact information. | - Contains copyright info.<br>- Links to Terms, Privacy Policy, and Contact.<br>- Consistent background color and small text style. |
| **Search Bar** | Allows users to search for properties by keyword, location, or availability. | - Text input field.<br>- Search button with icon.<br>- Optional filters for check-in/out dates and guests. |
| **Booking Summary Card** | Displays key details of a user’s selected property and booking info during checkout. | - Property thumbnail.<br>- Check-in/check-out dates.<br>- Total price and breakdown.<br>- Confirm booking button. |
| **Review Component** | Shows user reviews and ratings for each listing. | - Star rating system.<br>- User avatar and comment.<br>- Pagination or “load more” feature. |

---

