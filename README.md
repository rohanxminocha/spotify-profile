# Splotify

A web app for visualizing personalized Spotify data. View your top artists, top tracks, recently played tracks, and detailed audio information about each track. Create and save new playlists of recommended tracks based on your existing playlists and more.

Built using [Spotify Web API](https://developer.spotify.com/documentation/web-api/), [Create React App](https://github.com/facebook/create-react-app), [Express](https://expressjs.com/), [Reach Router](https://reach.tech/router), and [Styled Components](https://www.styled-components.com/).

## Project Setup

1. [Register a Spotify App](https://developer.spotify.com/dashboard/applications) and add `http://localhost:8888/callback` as a Redirect URI in the app settings
1. Create an `.env` file in the root of the project based on `.env.example`
1. `nvm use`
1. `yarn && yarn client:install`
1. `yarn dev`
