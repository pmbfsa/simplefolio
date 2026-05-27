<div align="center">

# 🌐 Simplefolio — Personal Portfolio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en/docs/Web/HTML) [![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en/docs/Web/JavaScript) [![Parcel](https://img.shields.io/badge/Parcel-B0731B?style=for-the-badge&logo=parcel&logoColor=white)](https://parceljs.org/)

My personal portfolio, designed to showcase published projects and make professional contact easier.

**[→ Visit my portfolio](https://pmbfsa.github.io/simplefolio/)**

</div>

## 📋 About the Project

This portfolio was built with a focus on **simplicity and performance**, bringing together in one place:

- 🗂️ Links to published projects
- 📄 Access to my resume
- 📞 Direct contact buttons via phone and e-mail
- 📱 Responsive layout for all devices
- ✨ Animations for a smoother experience

## 📸 Screenshot

<div align="center">
  <img src="./examples/example.png" alt="Paulo Márcio's portfolio preview" width="100%">
</div>

## 🚀 Tech Stack

| Technology     | Role                                                 |
| -------------- | ---------------------------------------------------- |
| **HTML5**      | Semantic structure and markup                        |
| **CSS3**       | Styling and responsive layout                        |
| **Sass/SCSS**  | CSS pre-processing with variables and modularization |
| **JavaScript** | Interactivity and dynamic behavior                   |
| **Parcel**     | Bundler for packaging and building the project       |

## ✨ Features

- **Responsive** — adapted for mobile devices, tablets, and desktops
- **Animations** — transitions and visual effects to enhance user experience
- **Direct contact** — shortcut buttons for phone calls and e-mail
- **Resume access** — direct link to download or view the CV
- **Project links** — dedicated section for published projects

## 🛠️ Running Locally

### Prerequisites

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [npm](https://www.npmjs.com/)

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/pmbfsa/simplefolio.git

# 2. Navigate to the project folder
cd simplefolio

# 3. Install dependencies
npm install

# 4. Start the development server
npm run start
```

The project will be available at `http://localhost:1234` (Parcel's default port).

## 📦 Production Build

```bash
npm run build
```

Optimized files will be generated in the `docs/` folder, which is used for publishing via **GitHub Pages**.

## 🌍 Deploy

The project is published via **GitHub Pages** from the `docs/` folder on the `main` branch.

Live at: [https://pmbfsa.github.io/simplefolio/](https://pmbfsa.github.io/simplefolio/)

## 📁 Project Structure

```
simplefolio/
├── src/
│   ├── assets/
│   │   ├── favicon.png             # Site icon
│   │   ├── omnifood.png            # Project image
│   │   ├── profile.jpeg            # Profile photo
│   │   └── resume.pdf              # Resume
│   ├── data/
│   │   └── scrollRevealConfig.js   # ScrollReveal animation settings
│   ├── sass/                       # Sass environment configuration files
│   ├── scripts/
│   │   ├── scrollReveal.js         # Scroll animation script
│   │   └── tiltAnimation.js        # Tilt animation script
│   ├── index.html                  # Main page
│   ├── index.js                    # JavaScript entry point
│   └── styles.scss                 # Global styles (Sass)
├── docs/                           # Production build (GitHub Pages)
├── examples/
│   └── example.png                 # Portfolio screenshot
├── package.json
├── LICENSE
└── README.md
```

## 📬 Contact

Developed by **Paulo Márcio**

[![GitHub](https://img.shields.io/badge/GitHub-pmbfsa-181717?style=for-the-badge&logo=github)](https://github.com/pmbfsa)

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.
See the [LICENSE](./LICENSE) file for more details.
