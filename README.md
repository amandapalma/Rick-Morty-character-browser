# Rick & Morty Character Browser

<img width="300" src="src/images/Rick_and_Morty_-_logo.png" alt="Rick and Morty logo">

**Demo:** https://amandapalma.github.io/Rick-Morty-character-browser/

A web app to search and explore characters from the Rick & Morty series, built with React as the final evaluation project of the [Adalab](https://adalab.es/) bootcamp. It shows the first characters returned by the [Rick and Morty API](https://rickandmortyapi.com/), sorted alphabetically, and lets you filter them by name.

## Screenshots

**Home**

![Home](src/images/screenshots/home.png)

**Details page**: clicking a character opens a detail card (species, status, origin planet and number of episodes).

![Details Card](src/images/screenshots/detailsCard.png)

**Error screens**: you get one of these if you type a search with no results, use a wrong route, or open a character's details with a wrong id.

![Search not found](src/images/screenshots/searchNotfound.png)
![Route not found](src/images/screenshots/routeNotFound.png)
![Character Id not found](src/images/screenshots/characterIdNotFound.png)

## Stack

- [React](https://reactjs.org/) with [React Router](https://reactrouter.com/)
- [Sass](https://sass-lang.com/) for styles
- [Font Awesome](https://fontawesome.com/) icons
- [PropTypes](https://github.com/facebook/prop-types) for props validation
- Data from the [Rick and Morty API](https://rickandmortyapi.com/)

## Getting started

```
npm install
npm start
```

Open http://localhost:3000 to view it in the browser.

## Scripts

| Command | What it does |
| --- | --- |
| `npm start` | Runs the app in development mode. |
| `npm run build` | Builds the app for production in the `build` folder. |
| `npm run docs` | Builds the app and moves it to the `docs` folder, which GitHub Pages serves. |

## Author

Amanda Palma · [LinkedIn](https://www.linkedin.com/in/amanda~palma/) · [GitHub](https://github.com/amandapalma)
