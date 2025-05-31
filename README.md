# 🎬 Movie Search Engine

![Project Screenshot](https://www.mediafire.com/convkey/c72e/s9d2u0yd29lt32l7g.jpg)

A professional movie search application that provides detailed information about films directly in your browser. Built with HTML, CSS, and JavaScript.

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](#live-demo)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](#license)

## Features ✨

- **Instant Movie Search** - Find detailed information about any film
- **Comprehensive Details** - Get genre, cast, directors, writers, box office, awards and ratings
- **Beautiful UI** - Professional layout with glassmorphism design
- **Responsive Design** - Works perfectly on all devices
- **Visual Ratings** - Star-based rating system for intuitive scoring
- **Sample Data** - Preloaded information for popular movies

## Live Demo

[Try it now!](https://mrp44rth.github.io/movie) (Click to use the live application)

## How to Use 🚀

1. **Enter a movie name** in the search box (e.g., "The Dark Knight")
2. **Click "Search Movie"** or press Enter
3. **View detailed information** about the movie
4. **Explore** cast, ratings, box office collection, and more

## Technologies Used 🔧

- **HTML5** - For page structure
- **CSS3** - For styling and animations
- **JavaScript** - For functionality and data handling
- **Font Awesome** - For beautiful icons
- **Glassmorphism Design** - Modern UI technique

## Browser Support 🌐

| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Edge    | ✅ Full |
| Safari  | ✅ Full |
| Mobile Browsers | ✅ Full |

## Setup Instructions

No setup required! Simply:

1. Copy the HTML code
2. Save as `index.html`
3. Open in any modern browser

## Sample Movies Included

- The Dark Knight
- Inception
- Avengers: Endgame
- Titanic
- The Matrix

## Preview

```mermaid
graph LR
    A[User Enters Movie Name] --> B[Search Initiated]
    B --> C{Data Found?}
    C -->|Yes| D[Display Movie Info]
    C -->|No| E[Show Error Message]
    D --> F[Show Poster, Title, Description]
    D --> G[Show Genre, Actors]
    D --> H[Show Directors, Writers]
    D --> I[Show Box Office, Awards]
    D --> J[Show Ratings]
