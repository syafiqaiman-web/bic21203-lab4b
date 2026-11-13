# Lab #4b: Client-Side Scripting (JSON and jQuery)

**Course:** BIC21203 Web Development  
**Topic:** Web page development using JSON, modern JavaScript, and jQuery  

## Overview
This repository contains the files for Lab #4b. The purpose of this lab is to demonstrate how to retrieve, parse, and display JSON data using modern JavaScript (`fetch` API) and to compare native DOM operations with jQuery.

## File Structure
*   `books.json`: A valid JSON dataset containing a collection of books.
*   `books.html`: An HTML page that fetches and displays the data from `books.json` using native JavaScript.
*   `jquery-dom.html`: An HTML page demonstrating DOM manipulation and event handling using jQuery 4.0.0.

## Setup Instructions
To run this project properly, the files must be served through a local development server. Opening `books.html` directly via the file explorer (using `file:///`) will cause CORS/security errors and block the `fetch()` API.

### Option 1: Using XAMPP (Recommended)
1. Ensure XAMPP is installed on your machine.
2. Clone or download this repository.
3. Move the project folder to your XAMPP `htdocs` directory (e.g., `C:\xampp\htdocs\lab4b`).
4. Open the XAMPP Control Panel and start the **Apache** module.
5. Open your web browser and navigate to:
   * `http://localhost/lab4b/books.html`
   * `http://localhost/lab4b/jquery-dom.html`

### Option 2: Using VS Code Live Server
1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension by Ritwick Dey.
3. Open `books.html` or `jquery-dom.html`.
4. Click the **"Go Live"** button in the bottom-right corner of the VS Code window, or right-click the code and select **"Open with Live Server"**.
5. Your browser will automatically open the correct local server URL (e.g., `http://127.0.0.1:5500/books.html`).

## Screenshots

### Question 1: Valid JSON
![alt text](<PICTURE/FIGURE 1.png>)

### Question 2: JSON Fetch Output
![alt text](<PICTURE/FIGURE 21.png>) 
![alt text](<PICTURE/FIGURE 22.png>)
![alt text](<PICTURE/FIGURE 23.png>)
### Question 3: jQuery DOM Output
![alt text](<PICTURE/FIGURE 3.1.png>)
![alt text](<PICTURE/FIGURE 3.2.png>) 