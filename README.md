# 2024 Paris Olympics Embedded Viewer

This project is designed to allow users CBC livestreams of the 2024 Paris Olympics and access an archive for rewatching videos, hosted on [GitHub Pages](https://missile.github.io/paris2024/). CBC content is region-locked to Canada. If you are accessing the page from outside of Canada, you may not be able to view the livestreams during the events or the videos after they end.

## Capabilities

- **Livestream Viewing**: Watch individual or multiple CBC broadcasts of the 2024 Paris Olympics directly from the webpage.
- **Archived Videos**: Access a daily archive of embedded videos to rewatch any event from previous days.
- **Dynamic Content**: The webpage dynamically updates to display the current day's livestream and archives the previous days' events.
- **Date Navigation**: Easily navigate between different days using the date-based links.

## Project Structure

- **index.html**: The main HTML file for the project, containing the structure of the page and links to the livestream and archive.
- **events/**: A folder containing individual HTML files for each day's single and multi-event streams.

## How It Works

- **Dynamic Date and Links**: The webpage automatically calculates the current day of the Olympics and displays the relevant livestream links at the top of the page. Past days are moved to the archive section below.
- **Date Format**: Each day is formatted as `"Date : Buttons"` (e.g., `August 11, 2024 : Day 16 Single | Day 16 Multi`), where the date appears on the left and the buttons linking to the day's videos appear on the right.
- **Day 16 Handling**: Once Day 16 has passed, it is automatically moved to the archive section.
