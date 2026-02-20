# Travel Journal

A beautiful and interactive React application for documenting and sharing travel experiences. Built with modern web technologies, this app showcases travel destinations with images, descriptions, and location maps.

## 📋 Features

- **Reusable Components**: Modular `Header` and `Entry` components for easy maintenance
- **Data-Driven**: Entries are powered by a centralized `data.js` file for easy updates
- **Google Maps Integration**: Quick links to view each destination on Google Maps
- **Responsive Design**: Clean, card-based layout that works across devices
- **Dynamic Entry Cards**: Each entry displays location details, dates, images, and descriptions

## 🛠️ Tech Stack

- **React** (v19.0.0-rc) - Modern UI library
- **Vite** - Fast build tool and dev server
- **JavaScript (JSX)** - Component markup language
- **CSS** - Styling and layout

## 🚀 Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/tuongdominhwork/Travel-Journal---HTML---CSS---React-Project.git
cd Travel\ Journal
```

2. Install dependencies:
```bash
npm install
```

### Run in Development

Start the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173` (or your Vite default port).

## 📦 Available Scripts

- `npm run dev` - Start development server with hot module reloading
- `npm run start` - Alias for `dev`
- `npm run build` - Create optimized production build
- `npm run preview` - Preview production build locally

## 📁 Project Structure

```
Travel Journal/
├── src/
│   ├── main.jsx              # React app entry point
│   ├── App.jsx               # Main App component
│   ├── App.css               # App styles
│   ├── index.css             # Global styles
│   └── assets/               # Static assets
├── components/
│   ├── Header.jsx            # Header component with logo and title
│   └── Entry.jsx             # Individual entry card component
├── images/
│   ├── globe.png             # Header globe icon
│   └── marker.png            # Map marker icon for entries
├── data.js                   # Travel entries data
├── package.json              # Project dependencies
├── vite.config.js            # Vite configuration
├── index.html                # HTML template
└── README.md                 # This file
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
