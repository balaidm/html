# 🔍 Query Parameters Viewer

This project is a lightweight HTML tool that displays all query parameters from the current page's URL. It's ideal for debugging, learning, or demonstrating how query strings work in web development.

## 📄 File Overview

- `index.html`: A standalone HTML file with embedded JavaScript and CSS. It reads the URL's query string and renders each parameter as a list item.

## 🚀 What It Does

When you open `index.html` with query parameters in the URL, the page will:

- Parse the query string using `URLSearchParams`
- Display each key-value pair in a clean, styled list
- Show a fallback message if no parameters are present

### Example

Opening the page with:

https://balaidm.github.io/html/index.html?user=Bala&role=admin&debug=true


Will render:

- **user**: Bala  
- **role**: admin  
- **debug**: true

## 🧪 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/balaidm/html.git
Open index.html in your browser.

2. Append query parameters to the URL to test:
    ```bash
    file:///path/to/index.html?foo=bar&test=123

## 🛠️ Technologies Used
HTML5

Vanilla JavaScript

Inline CSS

## 📚 Use Cases
Debugging query strings in web apps

Lightweight tool for frontend developers

---
