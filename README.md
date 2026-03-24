# Artifact Hunt

Artifact Hunt is a web application idea for my milestone project. The purpose of this project is to help users explore real museum artifacts in a simple and interactive way while I apply the JavaScript concepts covered in class, especially asynchronous programming, API integration, and array methods.

This project uses The Metropolitan Museum of Art Collection API. The base URL is `https://collectionapi.metmuseum.org/public/collection/v1`. The endpoint templates are `/search?hasImages=true&q={keyword}` and `/objects/{objectID}`. Working examples are `https://collectionapi.metmuseum.org/public/collection/v1/search?hasImages=true&q=samurai` and `https://collectionapi.metmuseum.org/public/collection/v1/objects/436535`.

The planned features include keyword-based artifact search, filtering results by department, image availability, and date range, and sorting results by title, year, or artist name. The interface will show artifact cards with key details such as image, title, artist, and period. I also plan to include loading and error states so the app behaves properly during API requests.

The technologies involved in this project are HTML, CSS, JavaScript (ES6 modules), NPM, and the Fetch API. Git and GitHub will be used for version control and submission.

To set up and run the project, clone the repository, move into the project folder, and start a local server. A basic run flow is:

```bash
git clone https://github.com/singhshouryat2-maker/artifact-hunt.git
cd artifact-hunt
npx serve .
```

