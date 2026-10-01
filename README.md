# 🎵 Spotify Web Player Clone

A clean and responsive **Spotify Web Player UI Clone** built using **HTML5 and CSS3**. This project recreates the visual structure and layout of Spotify's web player, including the sidebar navigation, library section, music cards, navigation bar, and bottom music player interface.

> **Note:** This project is currently a frontend UI implementation. It does not include JavaScript-based music playback, authentication, backend services, playlists, search functionality, or database integration.

---

## 📌 Project Overview

This project is designed to reproduce the core visual experience of the Spotify Web Player using simple frontend technologies.

The interface contains:

- 🏠 Home navigation
- 🔍 Search navigation
- 📚 Your Library section
- ➕ Create playlist option
- 🎙️ Podcast discovery section
- ⬅️➡️ Navigation controls
- 👤 User profile icon
- 🎵 Recently Played section
- 🔥 Trending music section
- 📊 Featured Charts section
- 🎧 Bottom music player
- ⏮️ Previous track control
- ▶️ Play/Pause interface
- ⏭️ Next track control
- 🔊 Playback progress bar
- 📱 Responsive layout adjustments

The project focuses primarily on **UI design, layout, styling, responsiveness, and visual similarity** to Spotify.

---

## ✨ Features

### 🏠 Navigation Sidebar

The left sidebar contains:

- Home
- Search
- Your Library
- Create Playlist
- Browse Podcasts

The sidebar uses a dark Spotify-inspired design with hover effects.

### 🎶 Music Sections

The main content area contains several music categories:

#### Recently Played

Displays recently played content using Spotify-style cards.

#### Trending Now Near You

Displays popular tracks with:

- Album artwork
- Song title
- Artist information

#### Featured Charts

Displays popular Spotify-style charts such as:

- Top Songs - Global
- Top Songs - India
- Top 50 - Global

### 🎧 Music Player

A fixed bottom music-player interface contains:

- Previous track button
- Previous/next controls
- Play button
- Next track button
- Playback progress bar
- Current time
- Total duration

The current implementation is a **visual music-player interface** and does not actually play audio.

### 📱 Responsive Design

The layout includes CSS media queries to adapt the interface for smaller screen sizes.

For example, some navigation elements are hidden when the viewport becomes narrower.

### 🎨 Hover & Interaction Effects

The UI includes several CSS interactions:

- Navigation hover effects
- Card zoom effects
- Button hover effects
- Button active states
- Music control hover effects
- Play button scaling effect

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and content |
| **CSS3** | Styling, layout, animations and responsiveness |
| **Font Awesome** | Navigation and interface icons |
| **Google Fonts** | Montserrat typography |
| **PNG/JPEG Assets** | Album artwork and UI graphics |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
```

Navigate into the project:

```bash
cd Spotify-Clone-main
```

### 2. Open the Project

Since this is a static HTML/CSS project, no installation or dependency setup is required.

You can simply open:

```text
index.html
```

in a web browser.

---

## 💻 Recommended Method — VS Code

For a better development experience, open the project in **Visual Studio Code**.

### Step 1

Open the project folder in VS Code.

### Step 2

Install the **Live Server** extension.

### Step 3

Right-click:

```text
index.html
```

and select:

```text
Open with Live Server
```

The website will open automatically in your browser.

---

## 🌐 External Resources

The project currently uses the following external resources:

### Font Awesome

Used for interface icons such as:

- Home
- Search
- Plus
- User
- Download
- Navigation icons

Font Awesome is loaded through its CDN.

### Google Fonts

The project uses the **Montserrat** font family from Google Fonts.

---

## 🎨 Design

The project follows a Spotify-inspired dark interface.

### Main Color Palette

| Element | Color |
|---|---|
| Page background | `#000000` |
| Main content | `#121212` |
| Cards | `#232323` |
| Primary text | `#FFFFFF` |
| Secondary text | Semi-transparent white |
| Progress indicator | `#1BD760` |

The design uses:

- Rounded cards
- Dark surfaces
- White typography
- Green playback indicator
- Hover transitions
- Flexible card layout

---

## 📱 Responsive Behavior

The project includes a responsive breakpoint:

```css
@media (max-width: 1000px)
```

At smaller viewport widths, selected navigation elements are hidden to provide more space for the main content.

The music cards also use a flexible layout:

```css
.cards-container {
    display: flex;
    flex-wrap: wrap;
}
```

This allows cards to move onto multiple rows depending on the available screen width.

---

## ⚙️ Current Functionality

### Implemented

- [x] Spotify-inspired UI
- [x] Sidebar navigation layout
- [x] Library section
- [x] Music cards
- [x] Album artwork
- [x] Featured charts
- [x] Bottom music-player UI
- [x] Playback progress-bar UI
- [x] Hover animations
- [x] Button interactions using CSS
- [x] Responsive behavior
- [x] Custom local assets
- [x] Google Fonts integration
- [x] Font Awesome integration

---

## ⚠️ Disclaimer

This project is a **Spotify-inspired educational frontend project** created for learning and demonstration purposes.

It is **not affiliated with, endorsed by, or sponsored by Spotify**.

Spotify, its logo, branding, and related trademarks belong to their respective owners.

The project should not be used to impersonate Spotify or distribute copyrighted music without appropriate authorization.

---

## 👨‍💻 Author

**Ratnesh**

Engineering Student

GitHub:

**https://github.com/Ratnesh-Coder**

---

## 📄 License

This project is intended for **educational and personal learning purposes**.

If you modify or distribute the project, ensure that any third-party assets, fonts, icons, music, or images are used according to their respective licenses.

---

## 🎵 Spotify Web Player Clone

### Music for everyone.

A Spotify-inspired frontend interface built with HTML5 and CSS3, demonstrating modern dark-theme UI design, responsive layouts, music cards, navigation, and a visual music-player interface.
