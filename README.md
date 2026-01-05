# ✨ Memories of Light
### Sky: Constellations of Memory

![Banner Image](https://via.placeholder.com/1200x400?text=Memories+of+Light+Banner) <!-- Replace with an actual screenshot of your starfield -->

> *"A digital sanctuary to preserve the fleeting moments of our journey through the clouds."*

**Memories of Light** is an immersive web experience designed to capture and display shared memories from the game *Sky: Children of the Light*. Set against an interactive, starlit backdrop, users can leave anonymous notes that become part of a glowing constellation of community memories.

---

## 🌟 Features

-   **Interactive Starfield**: A responsive, parallax starfield background that reacts to mouse movement and touch, creating a sense of depth and flight.
-   **Collective Memory Wall**: A shared space where users can submit and view notes stored in real-time.
-   **Immersive Atmosphere**: Integrated background ambient music and soundscapes to match the game's emotional tone.
-   **Responsive Design**: Fully optimized for both desktop and mobile devices, ensuring a seamless experience across all screen sizes.
-   **Firebase Integration**: Real-time database interactions using Firestore and anonymous authentication for frictionless user contributions.

## 🛠️ Technology Stack

-   **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS
-   **Styling**: Custom CSS animations, Glassmorphism UI
-   **Fonts**: Google Fonts (Cinzel, Inter, Caveat, Cormorant Garamond)
-   **Backend**: Firebase (Firestore, Authentication)

## 🚀 Getting Started

### Prerequisites

You need a modern web browser to view this project. No server installations are strictly required for local viewing, but a local server is recommended to avoid CORS issues with modules.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/memories-of-light.git
    cd memories-of-light
    ```

2.  **Configuration**
    Ensure `firebase-config.js` is present in the root directory. If it is missing (due to `.gitignore`), create it with your project credentials:
    ```javascript
    export const firebaseConfig = {
        apiKey: "YOUR_API_KEY",
        authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
        projectId: "YOUR_PROJECT_ID",
        // ... other config values
    };
    ```

3.  **Run Locally**
    You can use a simple tool like `serve` or the VS Code "Live Server" extension.
    ```bash
    npx serve .
    ```
    Open your browser to `http://localhost:3000`.

## 📁 Project Structure

```
├── Images/              # Assets for galleries and UI
├── bg_music.weba        # Ambient background music
├── index.html           # Main entry point
├── firebase-config.js   # Firebase configuration
└── README.md            # Project documentation
```

## 🎨 Credits

-   **Design Inspiration**: *Sky: Children of the Light* by thatgamecompany.
-   **Fonts**: Google Fonts.
-   **Icons**: FontAwesome & Custom SVGs.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/yourusername">Your Name</a>
</p>
