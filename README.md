# FitPlanHub

FitPlanHub is a modern, high-energy fitness platform connecting certified trainers with fitness enthusiasts. This project is a **frontend prototype** built with React, focusing on a premium, "Neon Sport" aesthetic and seamless user experience.

## 🚀 Project Overview

FitPlanHub serves two main user roles:
*   **Trainers:** Create and manage workout plans, view sales analytics, and build their brand.
*   **Members:** Explore fitness plans, subscribe to unlock content, follow trainers, and track their feed.

## ✨ Key Features

*   **Role-Based Authentication:** Distinct dashboards and flows for Trainers vs. Members (simulated auth).
*   **Interactive Trainer Dashboard:**
    *   Create new fitness plans with details (duration, price, description).
    *   Visual analytics for sales and subscribers.
    *   Plan management (Edit/Delete).
*   **Plan Marketplace:**
    *   Rich, visual plan cards with hover effects.
    *   **Content Locking:** Non-subscribers see previews; subscribers unlock full daily schedules.
    *   Mock payment flow for subscriptions.
*   **Social & Feed:**
    *   Follow/Unfollow trainers.
    *   Personalized feed showing new plans from followed trainers.
    *   Trainer profiles with bio, stats, and plan listings.
*   **Design System:**
    *   **Theme:** Dark mode by default with electric green (`#84cc16`) accents.
    *   **Typography:** `Oswald` (Headings) + `Inter` (Body) for a bold, athletic look.
    *   **Visuals:** Glassmorphism effects, neon glows, and high-quality stock imagery.

## 🛠️ Tech Stack

*   **Frontend:** React, TypeScript, Vite
*   **Styling:** Tailwind CSS (v4), Custom CSS variables, `lucide-react` icons
*   **Routing:** `wouter`
*   **State Management:** React Context (Auth), React Query
*   **Mock Data:** All data (users, plans, trainers) is mocked client-side for rapid prototyping.

## 🏃‍♂️ Getting Started

1.  **Install Dependencies:**
    ```bash
    npm install
    ```

2.  **Run Development Server:**
    ```bash
    npm run dev:client
    ```

3.  **Explore the App:**
    *   Visit `http://localhost:5000` (or the Replit Webview URL).
    *   **Login as Member:** Use the pre-filled demo credentials.
    *   **Login as Trainer:** Switch the tab on the login page and use the trainer credentials.

## 📂 Project Structure

*   `client/src/pages`: Main view components (Landing, Dashboard, Feed, etc.).
*   `client/src/components`: Reusable UI components (PlanCard, Layout, UI primitives).
*   `client/src/lib/mock-data.ts`: Centralized mock data for the prototype.
*   `client/src/context`: React Context providers (Auth).

---

*Built with Replit Agent*
