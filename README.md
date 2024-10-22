Project Title: Company Information Display
Description
This project is a simple HTML document that uses JavaScript to display company data from a JSON structure. The script includes two example companies: "Big Corporation" and "Small Startup." The project demonstrates how to parse and log specific company details using JavaScript's JSON.parse() method.

Features
The code defines a list of companies in JSON format.
It logs the name of the second company ("Small Startup") to the console.
Uses basic HTML structure with a JavaScript script embedded inside.
Technologies
HTML5: The basic structure of the webpage.
JavaScript: Handles parsing and logging JSON data.
Code Explanation
HTML Structure: The document uses a simple <html>, <head>, and <body> layout.

JavaScript: The company data is stored as a string in JSON format and parsed using JSON.parse(). The second company's name is then logged to the console.

javascript
Kopiera kod
let companies = `[
    {
        "name": "Big Corporation",
        "employees": 1000,
        "ceo": "Mary",
        "rating": 3.3
    },
    {
        "name": "Small Startup",
        "employees": 50,
        "ceo": null,
        "rating": 4.5
    }
]`;

console.log(JSON.parse(companies)[1].name); // Outputs: Small Startup
How to Run
Copy the provided HTML and JavaScript code into a .html file.
Open the file in a web browser.
Open the browser's developer tools (usually by pressing F12 or Ctrl+Shift+I).
Go to the "Console" tab, and you will see the name of the second company (Small Startup) logged.
Potential Improvements
Expand the JSON data to include more companies.
Display the information dynamically on the web page rather than logging it in the console.
Add user interactions to filter or sort the company data.
