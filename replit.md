# Senior Portfolio - Cesar Morales-Matute

## Overview
This is a static portfolio website showcasing student work from the 2024-2025 school year at Thomas A. Edison CTE HS. The portfolio contains CFUs (Check for Understanding), labs, games, and projects related to Web Development, Programming and Prototyping coursework.

## Project Type
Static HTML/CSS website with no backend or build process required.

## Technology Stack
- **Frontend**: HTML5, CSS3
- **Server**: Python 3 HTTP server (for development)
- **Design**: Custom CSS with Google Fonts (Raleway, Bebas Neue)

## Project Structure
```
.
├── index.html          # Main landing page
├── main.css            # Global stylesheet
├── server.py           # Simple HTTP server for development
├── images/             # Image assets
│   ├── background.jpg
│   ├── favicon.png
│   ├── ico.png
│   └── python.png
└── pages/              # Additional portfolio pages
    └── cfu.html        # Check for Understanding assignments
```

## Setup and Running
The project runs a simple Python HTTP server on port 5000:
- Server binds to 0.0.0.0:5000 for Replit compatibility
- Cache-Control headers disabled for instant refresh during development
- No build process or dependencies required

## Recent Changes
- **2025-11-07**: Initial Replit setup
  - Fixed CSS syntax errors (removed template placeholders)
  - Created Python HTTP server with cache control
  - Configured workflow for port 5000
  - Added .gitignore for Replit environment

## Notes
- Some navigation links reference pages that don't exist yet (labs.html, games.html, projects.html, about.html)
- Portfolio embeds Python code examples via CodeSkulptor iframes
- Color scheme: #E0E6FF, #676f9d, #424769, #2d3250, #f9b17a
