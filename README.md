# Price Check

A lightweight, minimal web application to quickly compare product prices across major e-commerce and quick-commerce platforms in India with a single click.

Instead of manually opening four different apps or tabs and retyping your item name every time, type it once here and instantly generate direct search links.

---

Link: [Github Pages](https://naina-bhatnagar.github.io/price-check/)

<img width="1537" height="1073" alt="image" src="https://github.com/user-attachments/assets/19b074d9-ff56-45aa-95b9-8407dd45c3c9" />

---

## Features

*   **Single-Input Search:** Type your product once to search across multiple platforms.
*   **Platform Support:**
    * **Amazon India** (E-commerce)
    * **Flipkart Minutes** (Quick-commerce / Hyperlocal)
    * **BigBasket** (Online Grocery)
    * **Blinkit** (Instant Delivery)
*   **Minimal & Elegant UI:** Clean aesthetic with smooth scrolling behavior and distinct brand color-coding.
*   **Zero Dependencies:** Built entirely using raw HTML, CSS, and vanilla JavaScript (`encodeURIComponent` handles the query parsing).

---

## How to Use

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Type a product name into the search box.
4. Press **Enter** or click **Search**.
5. Click on any store card to open that platform's live search page in a new tab.

---

## Code Structure

The project is completely self-contained within a single file:

*   `index.html`: Contains the layout framework, responsive CSS layout styles, and the core JavaScript search redirect script.

### Tech Stack Included
*   **HTML5** (Semantic structure)
*   **CSS3** (CSS Variables, Flexbox layout, and custom active-state micro-interactions)
*   **JavaScript** (DOM event listeners and dynamic URL construction)
