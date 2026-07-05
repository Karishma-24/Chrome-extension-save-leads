# 📌 Leads Tracker Chrome Extension

A simple Chrome Extension built while learning JavaScript through the Scrimba Full Stack Developer Path.

This extension allows users to save website URLs either by typing them manually or by saving the currently active browser tab. The saved links are stored locally in the browser and remain available even after closing Chrome.

---

## 📸 Preview

![Leads Tracker Screenshot](web_extension.png)

---

## ✨ Features

* Save custom URLs manually
* Save the currently active Chrome tab with one click
* Open saved links in a new tab
* Persistent storage using `localStorage`
* Delete all saved leads with a double-click confirmation
* Built using Chrome Extension Manifest V3

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Chrome Extension API (`chrome.tabs`)
* Local Storage API
* Manifest V3

---

## 📂 Project Structure

```
├── index.html
├── index.css
├── index.js
├── manifest.json
├── icon.png
└── README.md
```

---

## 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/leads-tracker.git
```

2. Open Chrome and navigate to:

```
chrome://extensions/
```

3. Enable **Developer Mode**.

4. Click **Load unpacked**.

5. Select the project folder.

6. Pin the extension from the Chrome toolbar and start saving your favorite websites!

---

## 📖 What I Learned

Through this project, I practiced:

* DOM manipulation
* Event listeners
* Arrays and loops
* Template literals
* Browser local storage
* JSON (`stringify` and `parse`)
* Chrome Extension development
* Chrome Tabs API
* Manifest V3 configuration

---

## 💡 Future Improvements

Some features I'd like to add in the future:

* Delete individual saved leads
* Edit existing links
* Add website titles instead of only URLs
* Export and import saved leads
* Search and filter saved links
* Categorize links using tags or folders
* Improve the UI with icons and animations

---

## 📸 Preview

> Add a screenshot or GIF of the extension here.

Example:

```
screenshots/preview.png
```

---

## 🙏 Acknowledgements

This project was built as part of the **Scrimba Full Stack Developer Path** to practice JavaScript fundamentals and Chrome Extension development.

---

## 📄 License

This project is intended for learning and personal portfolio purposes.
