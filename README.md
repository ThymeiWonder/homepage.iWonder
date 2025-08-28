# homepage.iWonder

A minimalist and elegant browser homepage with dynamic backgrounds and a multi-engine search bar.

[中文说明](README_zh.md)

## ✨ Features

- **🖼️ Dynamic Background:** A new random background image is selected from your personal collection every time you open the page.
- **🔍 Multi-Engine Search:** Seamlessly switch between Google, Bing, and Baidu. Your last selected search engine is automatically saved for your next visit.
- **🔮 Glassmorphism UI:** The search bar features a modern, semi-transparent "frosted glass" effect that blends beautifully with any background.
- **🚀 Smooth Animations:** The search bar appears and disappears with a fluid fade and slide animation.
- **⚙️ Persistent Settings:** Your preferred search engine and the visibility state of the search bar are saved locally in your browser, providing a consistent experience.
- **🖱️ Custom Interactions:** The right-click and middle-click actions are customized for quick and intuitive control.

## ⌨️ How to Use (Controls)

### Search Bar Visibility

- **To Show the Search Bar:**
  - **Keyboard:** Press any key (except `Esc`).
  - **Mouse (Left-click):** Click anywhere on the empty space of the page.
  - **Mouse (Right-click):** Right-click anywhere on the page when the search bar is hidden.

- **To Hide the Search Bar:**
  - **Keyboard:** Press the `Esc` key.
  - **Mouse (Middle-click):** Click the mouse wheel on the search bar (only works when the search input is empty).
  - **Mouse (Right-click):** Right-click anywhere on the page when the search bar is visible and the input is empty.

### Search Operations

- **Change Search Engine:** Click the search engine icon on the left of the search bar to open the dropdown menu, then select your desired engine.
- **Perform Search:** Type your query and press `Enter` or click the search icon on the right.

## 🔧 Customization

1.  **Background Images:**
    - Open the `homepage.iWonder.html` file.
    - Locate the `const images = [...]` array in the `<script>` section.
    - Replace the example file paths with the absolute paths to your own images.

2.  **Default Settings:**
    - In the same `<script>` section, you can find the `AppSettings` object.
    - *Note: These defaults are only used on the first load. Afterwards, your settings are saved in the browser's `localStorage`.*

## 🚀 Installation

It is recommended to use a browser extension to set this local HTML file as your new tab page.

- **For Microsoft Edge:** [Custom New Tab Page](https://microsoftedge.microsoft.com/addons/detail/ljabenhdllbfiglklhlmoecabdkmkjkp)

Set the URL in the extension to the local file path of `homepage.iWonder.html`.

## 👁️ Preview
1. **Search box visible:**
<img width="2559" height="1240" alt="image" src="https://github.com/user-attachments/assets/d1da0978-7cae-45b0-83a7-5e4cb8c590f2" />

2. **Search box hidden:**
<img width="2559" height="1240" alt="image" src="https://github.com/user-attachments/assets/9dbde707-8139-4e66-bcd5-f4f5ce433604" />


