# Juan Carlier — personal website

Live site: https://juancarlier.github.io/

This repository is a fork of [Jingdong Zhang’s website](https://github.com/Evergreen0929/Evergreen0929.github.io), retaining its homepage design, styles, animations, and cover imagery.

## Updating the website

- Edit [index.html](index.html) for biography, publications, research, and other content.
- Replace [the profile image](homepage_assets/juan-carlier.png) with a new PNG to update the portrait.
- Replace [the text CV](cv/Juan_Carlier_CV.txt) to update the download.
- Put small styling adjustments in [personal.css](assets/css/personal.css). The original [home.css](assets/css/home.css) and [home.js](assets/js/home.js) provide the template theme and interactions.

Push changes to `main` to publish automatically. [The deployment workflow](.github/workflows/pages.yml) uploads only this site's homepage and its required assets. Other files inherited from the original repository remain in source history and are not deployed.

For a local preview, run `python -m http.server 8000` from this folder and visit http://localhost:8000. No package installation or build step is required.
