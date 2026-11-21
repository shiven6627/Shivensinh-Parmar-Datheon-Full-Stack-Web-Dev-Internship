# Datheon Full Stack Web Development Internship

## Student Information

- **Full Name:** Shivensinh Parmar
- **Application ID:** `DT-2026-R65E8`
- **Internship:** Datheon — Full Stack Web Development Internship

---

## Project Overview

This repository contains three web development projects completed as part of the internship task submission. The projects demonstrate practical front-end development skills, JavaScript programming, API integration, browser storage, responsive user interface design, and interactive web application features.

### Task 2 — Task Manager

**Folder:** `task2-task-manager/`

A browser-based task management application that helps users organize and track their daily activities.

**Main features**
- Create new tasks with task details.
- View the task list and update existing tasks.
- Delete tasks and mark tasks as completed.
- Organize tasks using categories such as Work, Study, Personal, and Coding.
- Assign priority levels (High, Medium, and Low) and due dates.
- Search tasks and filter them by status or category.
- View task summary metrics, including total, pending, and completed tasks.
- Save task data in browser `localStorage`, so tasks remain available after refreshing the page.

**Technologies used:** HTML5, CSS3, JavaScript (ES6+), DOM Manipulation, and LocalStorage API.

### Task 3 — Weather Application

**Folder:** `task3-weather-app/`

A weather dashboard that allows users to search for a city and view its current weather information and upcoming forecast.

**Main features**
- Search for cities around the world.
- Use quick-search city shortcuts available in the interface.
- Display current weather information, including temperature, feels-like temperature, humidity, wind speed, pressure, and visibility where provided by the API.
- Display a five-day weather forecast.
- Update the interface theme according to weather conditions.
- Show loading feedback while weather information is being retrieved.
- Display an error message when a city cannot be found or a request fails.
- Retrieve location coordinates and weather information through public Open-Meteo APIs; no API key is required for the configured endpoints.

**Technologies used:** HTML5, CSS3, JavaScript (ES6+), Fetch API, Async/Await, Open-Meteo Geocoding API, and Open-Meteo Forecast API.

### Task 4 — E-commerce Store

**Folder:** `task4-ecommerce-store/`

A front-end e-commerce storefront where users can browse products, search and filter the catalog, manage a shopping cart, and complete a simulated checkout.

**Main features**
- Retrieve product information from FakeStoreAPI.
- Display product details such as images, names, descriptions, prices, and ratings.
- Filter products by category.
- Search products by title.
- Sort products by featured order, price, and customer rating.
- Add products to the shopping cart.
- Increase or decrease product quantities and remove items.
- Calculate the cart subtotal, tax, and shipping amount.
- Save cart information in browser `localStorage` so it remains available after a page refresh.
- Open a checkout form, enter shipping details, and complete a simulated checkout with an order confirmation.

**Technologies used:** HTML5, CSS3, JavaScript (ES6+), Fetch API, FakeStoreAPI, DOM Manipulation, and LocalStorage API.

> **Note:** Checkout and payment are simulated for demonstration purposes. This project does not process real payments or create real customer orders.

---

## Project Folder Structure

```text
Datheon_Internship_Submission/
│
├── README.md
│
├── task2-task-manager/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── task3-weather-app/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── task4-ecommerce-store/
    ├── index.html
    ├── style.css
    └── script.js
```

---

## How to Run the Projects

These are front-end projects and do not require a Node.js backend setup.

1. Download or extract the project folder.
2. Open the extracted folder in Visual Studio Code.
3. Open the required task folder.
4. Open its `index.html` file in a browser, or use the **Live Server** extension in Visual Studio Code.
5. For the Weather Application and E-commerce Store, ensure an internet connection is available because they retrieve data from external APIs.

### Run each project

- **Task Manager:** Open `task2-task-manager/index.html`.
- **Weather Application:** Open `task3-weather-app/index.html`.
- **E-commerce Store:** Open `task4-ecommerce-store/index.html`.

---

## Skills Demonstrated

- Structuring web pages with semantic HTML.
- Styling responsive interfaces with CSS.
- Writing interactive JavaScript using functions, events, arrays, and DOM manipulation.
- Implementing Create, Read, Update, and Delete (CRUD) operations in the browser.
- Using `localStorage` for client-side data persistence.
- Fetching and displaying external API data.
- Handling asynchronous operations with `async` and `await`.
- Implementing search, filtering, sorting, and dynamic UI updates.
- Providing loading, error, and user-feedback states.

---

## Submission Details

- **Submitted by:** Shivensinh Parmar
- **Application ID:** `DT-2026-R65E8`
- **Projects included:** Task 2 — Task Manager; Task 3 — Weather Application; Task 4 — E-commerce Store

