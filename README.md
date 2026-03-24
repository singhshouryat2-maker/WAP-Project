# Country Explorer JS

## Project Purpose
Country Explorer JS is a web application that helps users discover and compare countries using real API data.

The project is designed to practice JavaScript fundamentals from class, especially asynchronous programming (`fetch`, `async/await`, promises), array higher-order functions, and modular code structure.

## Public API Used
- API: REST Countries API
- Base URL: `https://restcountries.com`
- Endpoint used: `https://restcountries.com/v3.1/all`

Example endpoint with selected fields:
`https://restcountries.com/v3.1/all?fields=name,capital,region,subregion,population,area,flags`

## Planned Features
- Search countries by name and capital
- Filter countries by region
- Filter countries by population range
- Sort countries by:
  - Name (A-Z / Z-A)
  - Population (Low-High / High-Low)
  - Area (Low-High / High-Low)
- Responsive country cards with key details (flag, name, capital, region, population, area)
- Loading and error states during API requests

## How Course Topics Are Applied
- NPM for project initialization and scripts
- ES6 Modules (`import` / `export`) for separating API, UI, and logic
- Async JavaScript with `async/await`, promises, and `fetch`
- Array HOFs (`map`, `filter`, `find`, `sort`, `forEach`) for search/filter/sort/render operations
- Callback + `setTimeout` for debounced search (planned bonus)

## Technologies Involved
- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- NPM
- REST API (REST Countries)
- Git and GitHub

## Proposed Project Structure
```text
country-explorer-js/
  index.html
  style.css
  src/
    main.js
    api.js
    filters.js
    render.js
```

## Setup and Run (Basic)
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/country-explorer-js.git
   ```
2. Go to the project folder:
   ```bash
   cd country-explorer-js
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the project:
   ```bash
   npm run start
   ```

## Milestone Scope Note
This README is prepared for **Milestone 1 (planning and clarity)**. Core implementation starts in Milestone 2.

## Milestone Plan
- Milestone 1: Idea, API selection, GitHub repo, README
- Milestone 2: API integration + dynamic rendering + responsive layout
- Milestone 3: Search/filter/sort using array HOFs + interactive features
- Milestone 4: Refactor, final documentation, deployment
