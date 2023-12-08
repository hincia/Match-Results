# Football Match Results Parser

This is a simple JavaScript application that utilizes `XMLHttpRequest` to fetch football match results data from an external API. In this example, I am using the "Football Data" open API for football statistics. To use this API, you will need an access key, which you can obtain from their website.

## Getting Started

1. **Obtain API Key:** Visit [Football Data](https://www.football-data.org/) to get your API key.

2. **Replace API Key:** Replace 'YOUR_API_KEY' in the code with your obtained API key.

3. **Select Desired League:** Modify the `apiUrl` variable to choose the desired league. The example uses the endpoint for the English Premier League (`https://api.football-data.org/v2/competitions/PL/matches`).

4. **Run the Application:** Open the HTML file in a web browser to see the football match results.

## Code Overview

The application uses JavaScript and `XMLHttpRequest` to fetch data from the Football Data API. The fetched data is then displayed on the web page. The code is organized as follows:

- **getFootballResults:** Initializes an `XMLHttpRequest` to fetch football match results from the API.
- **displayResults:** Parses the fetched data and displays match results on the web page.

Feel free to customize the application based on your preferences or use it as a starting point for more advanced features.

**Note:** Remember to comply with the terms of use for the Football Data API.
