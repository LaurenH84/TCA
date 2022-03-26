# [![Netlify Status](https://api.netlify.com/api/v1/badges/3157ec0e-79e4-44d6-9561-7941b26f9826/deploy-status)](https://app.netlify.com/sites/festive-mestorf-cf09aa/deploys)

## Files of relevance
- `config.toml` contains site-wide configuration
- `config.json` contains parameters for the JavaScript code, which is primarily animation (e.g. scrolls and slides)
- `data/*.yml` contains content for each section
- `static/images` contains images (use JPEG for photos, and PNG for everything else)

## Deployments
### Automatic deployments
Deployments are automatically handled by [Netlify](https://www.netlify.com/) on push to the repository.
### Manual deployments
1) Install [hugo](https://gohugo.io/)
2) Install [git](https://git-scm.com/)
3) Run the following from a terminal
   ```
   $ git clone --recursive https://github.com/LaurenH84/TCA
   $ hugo
   ```
4) The necessary files will be generated in `./public`
