# 📦 QR Code Component – Frontend Mentor (Monorepo)

This repository contains two implementations of the **"QR Code"** component challenge from [Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H), organized in a **monorepo** structure.

Each implementation demonstrates a different approach using different technologies:

- `html-css/`: Pure HTML and CSS implementation
- `tailwind/`: Tailwind CSS v4 with local build system

---

## 📁 Project Structure

```
QRCODECOMPONENT/
├── html-css/                    ← Pure HTML and CSS version
│   ├── screenshots/
│   ├── src/
│   │   ├── assets/
│   │   ├── index.html
│   │   └── style.css
│   └── README.md
├── tailwind/                    ← Tailwind CSS v4 version
│   ├── screenshots/
│   ├── src/
│   │   ├── assets/
│   │   ├── index.html
│   │   └── input.css
│   ├── dist/
│   │   └── output.css
│   ├── package-lock.json
│   ├── package.json
│   └── README.md
├── .gitignore
└── README.md
```

---

## 📦 Requirements

To run the Tailwind CSS version, you need:
- [Node.js](https://nodejs.org/) (recommended: v18 or higher)
- npm (comes with Node.js)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AgilePanda482/QRCodeComponent-FrontendMentor.git
cd QRCodeComponent-FrontendMentor
```

### 2. HTML and CSS Version

**📂 Location:** `./html-css/`

No installation or dependencies required. Simply open the HTML file in your browser:

```bash
# Navigate to the HTML version
cd html-css/src/
# Open index.html in your browser
open index.html  # macOS
# or
start index.html # Windows
# also
xdg-open index.html #linux
# or just double-click the file
```

### 3. Tailwind CSS Version

**📂 Location:** `./tailwind/`

#### a. Install Dependencies

```bash
cd tailwind
npm install
```

#### b. Build CSS with Tailwind

```bash
npm run build:styles
```

> This command generates the `dist/output.css` file from `src/input.css` using Tailwind CSS v4.

#### c. Open the HTML File

Open `src/index.html` in your browser. The HTML file is already configured to load the generated CSS from the `dist/` folder.

```bash
# Open the HTML file
open src/index.html  # macOS
# or
start src/index.html # Windows
# also
xdg-open index.html # linux
```

---

## 🛠️ Development

### Tailwind CSS Development Mode

For active development with automatic rebuilding:

```bash
cd tailwind
npm run dev
```

This will watch for changes in your CSS and HTML files and rebuild automatically.

---

## 🖼️ Screenshots

Visual results for both implementations can be found in their respective screenshot directories:

- **HTML/CSS version:** `html-css/screenshots/`
- **Tailwind version:** `tailwind/screenshots/`

---

## 🎯 Challenge Details

This project is based on the [QR Code Component challenge](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H) from Frontend Mentor. The challenge focuses on:

- Responsive design implementation
- Clean, semantic HTML structure
- Modern CSS techniques
- Mobile-first approach

---

## 🧰 Technologies Used

### HTML/CSS Version
- Pure HTML5
- Vanilla CSS3
- CSS Flexbox for layout
- CSS custom properties (variables)

### Tailwind Version
- HTML5
- Tailwind CSS v4

---

## 📱 Browser Support

Both implementations support all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

---

## 👨‍💻 Author

**Sebastian Rico Vela**
- GitHub: [@AgilePanda482](https://github.com/AgilePanda482)
- LinkedIn - [@Agilepanda482](https://www.linkedin.com/in/agilepanda482/)

---

## 📝 License

This project is based on a [Frontend Mentor](https://www.frontendmentor.io/) challenge and is provided for educational and portfolio purposes only.

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for any improvements or additional implementations!

---