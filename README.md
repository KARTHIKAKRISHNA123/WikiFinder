# WikiFinder — Dynamic Wikipedia Search SPA

## Overview
WikiFinder is a performant, client-centric Single Page Application (SPA) architected using vanilla JavaScript, HTML5, and CSS3, designed to interface seamlessly with the Wikipedia REST API. It delivers asynchronous, low-latency query responses by leveraging the Fetch API with CORS-enabled endpoints, facilitating dynamic JSON payload parsing and rendering.

---

## Features
-   **RESTful API Integration:** Implements the Wikipedia MediaWiki API’s `action=query` endpoint with `list=search` to retrieve metadata-rich search results, optimized via URL-encoded query parameters.
-   **Asynchronous Data Handling:** Utilizes `async/await` syntax with robust error handling to manage promise-based HTTP requests and response parsing, ensuring non-blocking UI rendering.
-   **Debounced Input Processing:** Sanitizes and trims input values to prevent redundant API calls, minimizing rate limiting and optimizing performance.
-   **Dynamic DOM Manipulation:** Employs programmatic element creation with `document.createElement`, controlled insertion via `appendChild`, and innerHTML templating for result display.
-   **Thematic UI Toggling:** Implements a stateful dark/light theme toggle by dynamically manipulating CSS class lists on the root `<body>` element, adhering to accessibility and user preference standards.
-   **Responsive Design:** CSS Grid and Flexbox layout paradigms are employed to guarantee seamless rendering across viewport dimensions and device form factors.
-   **Modular and Maintainable Codebase:** JavaScript code segregated into discrete functions for separation of concerns, enhancing readability and future scalability.

---

## Technical Stack
-   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3 (Flexbox, CSS Variables)
-   **API:** Wikipedia MediaWiki API (JSON format, CORS-enabled)
-   **Tools:** Browser DevTools for network and performance profiling

---

## Installation & Usage
1.  Clone the repository:
    ```bash
    git clone [https://github.com/yourusername/wikifinder.git](https://github.com/yourusername/wikifinder.git)
    ```
2.  📂 Open the **`index.html`** file in any modern web browser (e.g., Chrome, Firefox, Edge).
3.  🔎 Enter your **search query** into the input field and submit to fetch real-time Wikipedia results.
4.  🎨 Toggle the **theme** using the "Light" / "Dark" button to switch the UI's appearance dynamically.
