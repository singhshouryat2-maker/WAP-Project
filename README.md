# Artifact Hunt

Artifact Hunt is my milestone web application idea where users can explore real museum artifacts in a simple and interactive way. I chose this topic because it is different from common movie or weather projects, and it still matches the JavaScript concepts covered in class.

In simple words, this project lets users search museum artifacts, apply filters, and sort results to quickly find what they want. It shows artifact details like image, title, artist, and year in an easy-to-read card format.

This project uses The Metropolitan Museum of Art Collection API. The base URL is `https://collectionapi.metmuseum.org/public/collection/v1`. I plan to use the search endpoint `/search?hasImages=true&q={keyword}` to find matching artifacts and the object endpoint `/objects/{objectID}` to load full details.

The main features planned for this project are keyword search, filtering, and sorting. Search will return artifacts related to user input. Filters will include department, image availability, and date range. Sorting options will include title, year, and artist name. Each result will be shown as an artifact card with image, title, artist, department, and date. When a user selects an item, the app will show additional object details from the API. The app will also include loading states, empty-result messages, and error handling for failed API requests. The layout will be responsive for both mobile and desktop screens.

The technologies used are HTML, CSS, JavaScript (ES6 modules), NPM, and the Fetch API, along with Git and GitHub for version control.

To set up and run the project locally, clone the repository, open the folder, and start a local static server:

```bash
git clone https://github.com/singhshouryat2-maker/artifact-hunt.git
cd artifact-hunt
npx serve .
```

This readme is fully handwritten by Shourya Singh. Also, I used Github Public Api's for my project.
