# React Fitness Application

A fitness/exercise browsing app built with **React** and **Material UI**. Search for
exercises, filter by body part, and view demonstrations and related workouts — powered
by the ExerciseDB API.

![React Fitness Application](https://i.ibb.co/Yt9spGc/image.png)

## Features

- 🔍 **Search exercises** by name, target muscle, or equipment
- 💪 **Filter by body part** with a horizontal scrolling menu
- 📄 **Exercise detail** pages with instructions and target muscles
- ▶️ **Exercise videos** and **similar exercises** suggestions
- 📱 Responsive Material UI layout with a hero banner

## Tech stack

`React` (Create React App) · `@mui/material` + `@emotion` ·
`react-router-dom` · `react-horizontal-scrolling-menu` · `react-loader-spinner` ·
ExerciseDB / YouTube Search APIs (via RapidAPI)

## Getting started

```bash
yarn install        # or: npm install
```

Create a `.env` file with your RapidAPI credentials (used by `src/utils/fetchData.js`):

```env
REACT_APP_RAPID_API_KEY=your_rapidapi_key
```

Then start the dev server:

```bash
yarn start          # http://localhost:3000
```

## Project structure

```
src/
├── components/     # HeroBanner, SearchExercises, Exercises, ExerciseCard,
│                   # ExerciseVideos, SimilarExercises, Navbar, Footer…
├── pages/          # Home, ExerciseDetail
├── utils/          # fetchData.js (API helpers)
└── assets/         # images & icons
```
