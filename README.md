# Climate News API
A simple API built with Express, Axios, and Cheerio to fetch and aggregate news articles related to climate change from various sources.

## Features
- Aggregates climate news articles from:
  - The Times
  - The Guardian
  - The Telegraph
  - BBC
  - New York Times

- API endpoints to fetch aggregated news.

## Getting Started
### Prerequisites
- Node.js
- npm

### Installation
- Clone this repository.
- Navigate to the project directory.
- Install the necessary dependencies: npm install

## Running the Application
To start the application run:
npm start

After starting the application, open a browser or a tool like Postman and navigate to:
http://localhost:8000/news
This will display the aggregated climate news articles from the predefined sources.

## Endpoints
- /: Welcome message
- /news: Returns the aggregated climate news articles

## Built With
- Express - Web application framework for Node.js
- Axios - Promise-based HTTP client for JavaScript
- Cheerio - Fast, flexible, and lean implementation of core jQuery designed specifically for the server

## Future Enhancements
- Caching to reduce redundant scraping.
- Adding more news sources.
- Filtering and searching capabilities.
