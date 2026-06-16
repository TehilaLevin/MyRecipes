# My Recipes: Interactive Voice-Guided Culinary Platform

A sophisticated web application designed to streamline the cooking experience through hands-free, voice-activated guidance. This project serves as a comprehensive recipe management system that allows users to interact with their culinary library through an automated text-to-speech engine.

---

View the Live Project


---

## Core Functionalities

* **Intelligent Text-To-Speech (TTS):** Integrated voice narration for recipe instructions, allowing for a hands-free environment during preparation.
* **Dynamic Playback Control:** User-controlled "Pause" and "Resume" functionality to sync the narration with real-time cooking progress.
* **Personalization Engine:** Dedicated settings interface to customize the interval between spoken lines and toggle between high-contrast or standard display modes.
* **User Authentication:** Secure login gateway for managing individual user profiles.
* **Recipe Management:** Robust dashboard featuring recipe search capabilities and the ability to append new entries to the collection.

---

## Technical Implementation

* **Architecture:** Developed using modular JavaScript to ensure the codebase is clean, efficient, and highly maintainable.
* **Data Persistence:** Utilizes localStorage for client-side data management, ensuring that user credentials, custom settings, and recipe lists persist across sessions.
* **Voice Integration:** Implements native browser speech synthesis to provide a fluid and responsive auditory experience.
* **Responsive Design:** Styled to be fully accessible across various devices, prioritizing user experience and interface clarity.

---

## System Architecture

The application is structured into four primary modules:

* **Authentication Module:** Handles user identification and access control via a login screen.
* **Configuration Dashboard:** Manages user-specific environmental variables such as narration speed and UI themes.
* **Discovery Layer:** A searchable interface for browsing and filtering the recipe collection.
* **Execution View:** The active cooking interface containing ingredients, methods, and playback controls.

---

## Optimization & Standards

The project adheres to strict coding standards, focusing on algorithmic efficiency and edge-case handling. All data structures are optimized for rapid retrieval from local storage to ensure seamless performance.
