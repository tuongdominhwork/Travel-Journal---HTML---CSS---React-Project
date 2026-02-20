# Travel Journal

A simple React + Vite app that renders travel journal entries as reusable cards.

## Features

- Reusable `Header` and `Entry` components
- Data-driven rendering from `data.js`
- External Google Maps links per location
- Clean, responsive-friendly card-style layout

## Tech Stack

- React
- Vite
- JavaScript (JSX)
- CSS

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

```bash
npm install
```

### Run in Development

```bash
npm run dev
```

The app starts on Vite's local dev server (usually `http://localhost:5173`).

## Available Scripts

- `npm run dev` - Start development server
- `npm run start` - Alias for dev server
- `npm run build` - Create production build
- `npm run preview` - Preview production build locally

## Project Structure

```text
Travel Journal/
├── App.jsx                  # App root: maps data into Entry components
├── index.jsx                # React entry point
├── index.css                # Global/component styles
├── data.js                  # Travel journal data source
├── components/
│   ├── Header.jsx           # Top navigation/header
│   └── Entry.jsx            # Individual travel card
├── images/
│   ├── globe.png
│   └── marker.png
└── index.html
```

## Data Model

Entries in `data.js` follow this shape:

```js
{
  id: 1,
  img: {
    src: "image-url",
    alt: "image alt text"
  },
  title: "Location title",
  country: "Country",
  googleMapsLink: "https://maps.google.com/...",
  dates: "Date range",
  text: "Description"
}
```

## Customization

- Add or edit places in `data.js`
- Update styles in `index.css`
- Change branding/title in `components/Header.jsx`

## License

This project is for learning and personal practice.
# Travel-Journal---HTML---CSS---React-Project
