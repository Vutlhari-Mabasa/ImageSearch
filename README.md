## 📷 Image Search Engine

A simple and responsive web application that allows users to search for images using the [Unsplash API](https://unsplash.com/developers). Users can enter any keyword to fetch and view relevant images, and load more results using a "Show More" button.


---

### ✨ Features

* Search for any type of image (nature, cars, animals, etc.)
* Results are displayed in a responsive 3-column grid
* Clickable images that open the full-size version on Unsplash
* “Show More” button to load additional pages
* Fully responsive and styled with custom fonts

---

### 🛠 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **Unsplash API**

---

### 📁 Folder Structure

```
.
├── index.html         // Main HTML file
├── style.css          // Stylesheet for layout and design
└── script.js          // JavaScript for API integration and interaction
```

---

### 🧠 How It Works

* On submitting a search, the app fetches image results from the Unsplash API using the keyword entered.
* The results are displayed as a grid of clickable images.
* Clicking “Show More” fetches more images using pagination.
* Each new search clears previous results to avoid stacking images.

---

### 🔑 API Key

To use this project with your own Unsplash account:

1. Sign up at [Unsplash Developers](https://unsplash.com/developers)
2. Create a new application to get an access key
3. Replace the value of `accessKey` in `script.js` with your key:

   ```js
   const accessKey = "YOUR_ACCESS_KEY_HERE";
   ```
