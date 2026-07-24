# Admin Dashboard

A desktop admin-dashboard interface built with semantic HTML and custom CSS. The project recreates a complete application shell with navigation, account controls, project summaries, announcements, and community activity while focusing on CSS Grid and Flexbox layout techniques.

[View the live demo](https://mohamedmosilhy.github.io/Admin-Dashboard/) · [View the source](https://github.com/mohamedmosilhy/Admin-Dashboard)

![Admin Dashboard](./assets/dashboard-project.png)

## Project overview

The page is organized into three primary areas:

- A persistent sidebar containing account, communication, and settings links
- A two-row header with search, notifications, profile information, and quick actions
- A dashboard workspace containing project cards, announcements, and trending profiles

This is a front-end presentation project. Navigation items, search, notifications, and action buttons are visual interface elements and are not connected to a backend.

## Features

- Ten-item sidebar navigation with locally stored SVG icons
- Search and notification controls in the top bar
- User greeting and avatar treatment
- New, Upload, and Share action buttons
- Two-column project card grid with status accent borders
- Announcement feed and trending-user panel
- Grid and Flexbox used together for the page and component layouts
- Local image and icon assets, with no JavaScript or build step

## Built with

- HTML5
- CSS3
- CSS Grid
- Flexbox
- Google Fonts (Roboto)

## Project structure

```text
Admin-Dashboard/
├── assets/       # Avatars, dashboard preview, and SVG icons
├── index.html    # Dashboard markup
├── styles.css    # Layout and visual styles
└── README.md
```

## Run locally

No dependencies are required. Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/mohamedmosilhy/Admin-Dashboard.git
cd Admin-Dashboard
```

For consistent asset loading, the folder can also be served with any static web server.

## Current scope

The current stylesheet targets the full dashboard layout and does not include dedicated mobile media queries. A future iteration could add a collapsible sidebar, functional controls, keyboard-friendly navigation, and application data.
