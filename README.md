# SEC Common Stock Shares Outstanding Viewer

## Summary
This single-page web application fetches and displays the maximum and minimum common stock shares outstanding for a given company directly from the SEC's API. By default, it shows data for 3M (MMM). Users can also provide a CIK as a query parameter to view data for other companies dynamically.

## Setup
This is a static site. To run it, simply open the `index.html` file in your web browser. No special server setup or build process is required.

## Code Explanation
- `index.html`: This is the main and only HTML file. It contains the structure of the web page, including placeholders for the company name, maximum shares outstanding, and minimum shares outstanding. It also includes an inline JavaScript block that handles data fetching, parsing, and rendering.
- `data.json`: This file stores the pre-processed share outstanding data for 3M, including the entity name, and the maximum and minimum shares outstanding figures for fiscal years greater than 2020.
- `uid.txt`: A unique identifier file as requested.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
