# adventureswithmarley.com

[![Netlify Status](https://api.netlify.com/api/v1/badges/725f70ed-7d1e-4ac2-b463-791cc837fb15/deploy-status)](https://app.netlify.com/sites/wonderful-saha-622e17/deploys)


## To-Do:
- Implement noindex, nofollow
- Add a manifest file - https://www.gatsbyjs.com/docs/tutorial/part-eight/

### Set up of the needed content model and create a configuration file

This project comes with a Contentful setup command `npm run setup`.

This command will ask you for a space ID, and access tokens for the Contentful Management and Delivery API and then import the needed content model into the space you define and write a config file (`./.contentful.json`).

`npm run setup` automates that for you but if you want to do it yourself rename `.contentful.json.sample` to `.contentful.json` and add your configuration in this file.

## Crucial Commands

### `npm run dev`

Run the project locally with live reload in development mode.

### `npm run build`

Run a production build into `./public`. The result is ready to be put on any static hosting you prefer.

### `npm run serve`

Spin up a production-ready server with your blog. Don't forget to build your page beforehand.
