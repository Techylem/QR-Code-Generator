# QR-Code-Generator
A lightweight, browser-based QR Code Generator built with HTML, JavaScript, and Tailwind CSS.
Generate clean QR codes instantly and download them in SVG format for use in print or digital projects.

Live Demo: https://techylem.github.io/QR-Code-Generator/

## 🚀 Features
- Generate QR codes from any text or URL
- Customizable size
- Select error-correction level (L, M, Q, H)
- Change foreground and background colors
- Editable filename before download
- Live preview panel
- Download output as SVG
- Fully client-side (no server required)

## 🛠️ Tech Stack
HTML5
Tailwind CSS (CDN)
JavaScript
QRious (4.0.2) for reliable QR generation

📂 Project Structure
|
|-- index.html        # Main app UI + logic
|-- README.md         # Project documentation
|-- /assets           # (Optional) Images or resources if added later

📦 How It Works
1. The app uses QRious to render a QR code on a canvas.
2. The canvas output is then embedded into a clean SVG wrapper, allowing the user to:
- preview the QR code
- download it as a vector graphic ready for print
- No dependencies beyond Tailwind CDN + QRious CDN.

## 🔧 Usage
Enter text or a URL in the input field.
Adjust size, error correction level, or colors if needed.
Click Generate.
Preview appears instantly.
Click Download SVG to save the QR code.


## 🤝 Contributions
Pull requests are welcome. If you want to enhance the UI, add PNG export, or add advanced styling features, feel free to submit improvements.

## 📜 License
This project is licensed under the MIT License.
You can use, modify, and distribute it freely.
