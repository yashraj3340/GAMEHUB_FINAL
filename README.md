Here’s the updated README file with the licensing and contributing sections removed:

---

# GameHub

Welcome to GameHub, a comprehensive platform for discovering and tracking video games. This project utilizes the RAWG API to provide detailed game information and enhance your gaming experience.

## Table of Contents

- [Installation](#installation)
- [Running the Development Server](#running-the-development-server)
- [API Information](#api-information)

## Installation

To get started with GameHub, you'll need to install the necessary dependencies. Follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yashraj3340/gamehub_final.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd gamehub_final
   ```

3. **Install Dependencies:**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then run:

   ```bash
   npm install
   ```

   This will install all the required dependencies listed in `package.json`.

## Running the Development Server

To start the development server and view GameHub in action, follow these steps:

1. **Run the Development Server:**

   ```bash
   npm run dev
   ```

   This will start the server and open GameHub in your default web browser.

2. **Access the Application:**

   Open your browser and go to `http://localhost:3000` to view the application.

## API Information

GameHub uses the [RAWG API](https://rawg.io/apidocs) to fetch game data. Here’s a brief overview of the API usage:

- **Base URL:** `https://api.rawg.io/api/`
- **API Key:** You’ll need to use your own API key to access the RAWG API. You can obtain one by signing up at [RAWG](https://rawg.io/).

### Example Endpoints

- **Get Games List:**

  ```
  GET /games
  ```

  - **Parameters:**
    - `key` - Your API key.
    - `page_size` - Number of results per page.
    - `page` - Page number.

- **Get Game Details:**

  ```
  GET /games/{id}
  ```

  - **Parameters:**
    - `id` - The ID of the game you want to retrieve details for.
    - `key` - Your API key.

For detailed API documentation, refer to the [RAWG API Docs](https://rawg.io/apidocs).

---

