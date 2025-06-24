# MargNiti - Personalized Learning Roadmap

MargNiti is a static web application designed to provide users with a personalized learning roadmap based on their chosen domain, such as "Coding" or "Data Science." It guides users through a series of learning levels, tracks their progress, and provides curated resources for each step.

## ✨ Features

- **User Sign-In**: Captures user's name, email, and preferred domain.
- **Persistent State**: Uses `localStorage` to remember the user and their progress.
- **Dynamic Roadmaps**: Generates a visual, step-by-step roadmap for the selected domain.
- **Progress Tracking**: Unlocks new levels as the user completes previous ones.
- **Resource Pages**: Each level has its own page with educational content and links to external resources (notes, videos).
- **Responsive Design**: Built with Tailwind CSS for a modern, mobile-friendly interface.

## 🚀 How to Run

This is a static website with no backend dependencies. To run it:

1.  Clone or download the repository.
2.  Open the `signin.html` file in your web browser.
3.  Enter your details and start your learning journey!

## 🛠️ Technologies Used

-   **HTML5**: The structure for all web pages.
-   **Tailwind CSS**: For utility-first styling and responsive design.
-   **JavaScript (ES6)**: For all client-side logic, including:
    -   Form validation.
    -   DOM manipulation.
    -   Routing via URL parameters (`?domain=...`).
    -   State management using `localStorage`.

## 📂 File Structure

The project follows a flat file structure for simplicity:

-   `signin.html`: The entry point and user registration page.
-   `home.html`: The user's dashboard, showing their domain and trendy topics.
-   `domain-roadmap.html`: The main page that displays the roadmap for a specific domain.
-   `level-*.html`: Individual pages for each level in the roadmaps (e.g., `level-basic-python.html`).
-   `README.md`: This file.
