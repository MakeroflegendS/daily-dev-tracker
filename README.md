# DevLog 🚀

A minimal, chronological daily study and project tracker. DevLog is designed to be a public-facing timeline of your daily work, featuring a hidden, secure "Admin Mode" that allows only the owner to add, edit, or delete entries.

## ✨ Features

* **Vertical Timeline UI:** A clean, chronological view of your daily tasks and project milestones.
* **Hidden Admin Mode:** A mock toggle in the navigation bar reveals an authentication modal for the owner.
* **Persistent Login:** Uses `localStorage` to keep you logged in "for life" once you enter the correct password.
* **Smart Hint System:** Displays a custom password hint only if an incorrect password is submitted.
* **Dynamic Tagging & Status:** Categorize entries by tech stack (e.g., `#React`, `#Tailwind`) and workflow status (`Started`, `Continued`, `Finished`).

## 🛠️ Tech Stack

* **Frontend:** HTML5, Vanilla JavaScript
* **Styling:** Tailwind CSS (via CDN for a zero-build setup)
* **Icons:** FontAwesome
* **Backend/Database:** Designed for **Firebase Firestore** (Authentication & Data Storage)

## 🚀 Getting Started

To run this project locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/devlog.git](https://github.com/yourusername/devlog.git)
