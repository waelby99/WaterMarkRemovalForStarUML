# 🧽 StarUML Watermark Remover (UNREGISTERED)

A lightweight **client-side web tool** that removes the **“UNREGISTERED” watermark** from images exported by **StarUML**.

This project uses **HTML5 Canvas** and **vanilla JavaScript** to detect and clean watermark pixels directly in the browser — **no backend, no uploads, no dependencies**.

---

## ✨ Features

- 📤 Upload images exported from StarUML  
- 🧠 Automatically detects StarUML watermark pixels  
- 🎨 Replaces the watermark with a white background  
- 📥 Download the cleaned image instantly  
- ⚡ Fast, lightweight, and works offline  

---

## 🛠️ How It Works

1. The image is rendered onto an HTML `<canvas>`
2. The script scans each pixel of the image
3. Light gray pixels (`RGB ≈ 204–254`) typical of the StarUML watermark are detected
4. Those pixels are replaced with white
5. The cleaned image can be downloaded as a PNG file

All processing happens **locally in the browser**.

---

## 🚀 Tech Stack

- HTML5  
- CSS  
- JavaScript (Canvas API)  

---

## 📦 Installation & Usage

### 🔹 Local Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/waelby99/WaterMarkRemovalForStarUML.git
    ```

2. **Navigate to the project folder:**
    ```bash
    cd WaterMarkRemovalForStarUML
    ```

3. **Open the application:**
    - Double-click `index.html`
    - **Or** open it in any modern web browser

---

### 🔹 Online Usage (No Installation)

You can use the tool directly via GitHub Pages:

👉 **[Live Demo](https://waelby99.github.io/WaterMarkRemovalForStarUML/)**

**Steps:**
1. Upload your StarUML exported image
2. Click **Nettoyer**
3. Click **Télécharger** to save the cleaned image

---

## ⚠️ Disclaimer

This tool is provided **for educational and personal use only**.  
Please respect StarUML’s license terms and use this project responsibly.

---

## 📄 License

MIT License
