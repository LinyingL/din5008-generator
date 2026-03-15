# DIN 5008 (Form A) Letter Generator

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)

An offline, privacy-first, zero-dependency HTML generator for professional German business letters complying with the strict **DIN 5008 Form A** typography and layout standards.

## ✨ Features

- **100% Offline & Privacy-First**: All data processing and PDF generation happen directly in your local browser sandbox. No server communication, no data leaks. Perfect for handling sensitive personal or corporate information.
- **Zero Dependencies**: It's just a single `index.html` file. No React, no Vue, no Node.js, no npm installs. Just open it in any modern browser.
- **Strict DIN 5008 Compliance**: 
  - Absolute positioning in millimeters (`mm`) for Form A address windows (Fensterbriefhüllen).
  - Accurate measurement for folding and punching marks (Falt- und Lochmarken).
  - Justified text alignment (Blocksatz) with native German automatic hyphenation (`hyphens: auto`).
- **Data Persistence**: Temporarily auto-saves drafts to your browser's LocalStorage to prevent accidental data loss.
- **Export & Import (JSON)**: Save your completed templates as `.json` files to your computer and reload them anytime.
- **Print to PDF**: Built-in CSS `@media print` logic cleanly removes the UI for a perfect, pixel-accurate A4 PDF generation via your browser's print dialog.

## 🚀 Usage

### Option 1: Try it Live (GitHub Pages)
*(Note: If you activate GitHub Pages for your repository, add the link here: `https://<your-username>.github.io/<repo-name>/`)*

### Option 2: Local Usage
1. Clone this repository or simply download the `index.html` file.
2. Double-click `index.html` to open it in Chrome, Edge, Safari, or Firefox.
3. Start typing in your sender/recipient details and the letter content.
4. Click **"Als PDF / Drucken"** (Print to PDF).
   > **Important Print Settings:** Ensure that "Headers and footers" are unchecked, and set scaling to Default/100% (do not use "Fit to page" or the millimeter accuracy will be skewed).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
