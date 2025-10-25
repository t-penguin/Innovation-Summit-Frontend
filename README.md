# AI Innovation Summit Fall 2025 Frontend

This project uses React and React-Router to display a Single-Page App and is based on the Capstone II Starting Point repository supplied for the Summer 2025 TTPR Bootcamp.

## Getting Started

This app works best in conjunction with a [Innovation Summit Backend](https://github.com/t-penguin/Innovation-Summit-Backend). Go to that repo and get it up and running so that this Frontend has an API to request data from.

With that done, run the following commands:

1. Clone or fork this repository on GitHub.
2. Install the NPM packages: `npm install`
3. Preview your React app: `npm run start-dev`

## Deployment

You should be able to deploy this application to Vercel by simply connecting the GitHub repo to a new Vercel project. You will also need to configure the `API_URL` environment variable on Vercel to match the deployed API url for your backend. Likewise, you may need to configure the `FRONTEND_URL` environment varialbe on your Backend to match the deployed URL for this app.

NOTE: If you are using Web Sockets, you should deploy to another Web Host that better supports it like Render. Unlike Vercel, which we have the config file for, Render's config is done on their dashboard. Instructions for how to set that up will be added here shortly.