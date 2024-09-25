# Random Joke Fetcher

This project is a simple web application that fetches and displays a random joke from an API. The user can click the "Get New Joke" button to fetch a new random joke. The app is built using React, TypeScript, and Tailwind CSS, and it utilizes the `official-joke-api` to retrieve jokes.

## Features

- Fetches a random joke using the [Official Joke API](https://official-joke-api.appspot.com/random_joke).
- Displays both the joke setup and punchline.
- Provides a button to fetch a new joke.
- Responsive design with Tailwind CSS for a modern UI.
- Error handling for failed API calls.

## Technologies Used

- **React**: For building the user interface.
- **TypeScript**: For type-safe JavaScript development.
- **Tailwind CSS**: For styling and responsive design.
- **Official Joke API**: For fetching random jokes.

## How It Works

1. The app fetches a random joke on page load using the `useEffect` hook.
2. A user can click the "Get New Joke" button to fetch another random joke.
3. The app displays the setup and punchline together in a card-like interface.
4. It handles errors gracefully if the joke fails to load.

## Code Overview

- **RandomJokeComponent**: 
  - Fetches a random joke from the API.
  - Displays the joke or a loading message.
  - Includes a button for fetching a new joke.
  
### `fetchJoke` Function
- Fetches the joke data from the API and updates the state.
- Handles errors by displaying a failure message in case the API request fails.

## Styling

- The app uses Tailwind CSS to achieve a clean and modern UI.
- The background has a gradient from red to purple.
- A joke card is displayed in the center of the screen.
- The button has a hover effect and rounded corners for better user interaction.

## How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/random-joke-fetcher.git
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```

4. Open the app at `http://localhost:3000`.

## Deployment

You can deploy this project using services like Vercel or Netlify. Below is a link of deployment of this project.

### [Deployment Link](#)

## API Reference

- [Official Joke API](https://official-joke-api.appspot.com/random_joke)
