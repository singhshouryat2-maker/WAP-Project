# Artifact Hunt

Artifact Hunt is my milestone web application idea where users can explore real museum artifacts in a simple and interactive way. I chose this topic because it is different from common movie or weather projects, and it still matches the JavaScript concepts covered in class.

This project uses The Metropolitan Museum of Art Collection API. The base URL is `https://collectionapi.metmuseum.org/public/collection/v1`. I plan to use the search endpoint `/search?hasImages=true&q={keyword}` to find matching artifacts and the object endpoint `/objects/{objectID}` to load full details. Example working URLs are `https://collectionapi.metmuseum.org/public/collection/v1/search?hasImages=true&q=samurai` and `https://collectionapi.metmuseum.org/public/collection/v1/objects/436535`.

The main features planned for this project are keyword-based search, filtering by department/image/date range, and sorting by title, year, or artist name. The UI will show artifact cards with key information such as image, title, artist, and date, and I will also handle loading and error states during API calls.

The technologies used are HTML, CSS, JavaScript (ES6 modules), NPM, and the Fetch API, along with Git and GitHub for version control.

To set up and run the project locally, clone the repository, open the folder, and start a local static server:

```bash
git clone https://github.com/singhshouryat2-maker/artifact-hunt.git
cd artifact-hunt
npx serve .
```

This README is prepared for Milestone 1 planning, and full implementation will be completed in the next milestones.
