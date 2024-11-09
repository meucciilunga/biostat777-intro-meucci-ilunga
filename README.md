## Project 1 - 140.777

This repository contains the source files, configuration, and style definitions for a Quarto-based website for Project 1 of the JHU-BSPH course 140.777. The website is built to showcase basic information about my academic and professional background.

Link to deployed site: **[https://meucciilunga.github.io/biostat777-intro-meucci-ilunga/](https://meucciilunga.github.io/biostat777-intro-meucci-ilunga/)**

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Customization](#customization)
- [File Overview](#file-overview)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

The website is built using [Quarto](https://quarto.org) and serves as a basic personal academic/professional portfolio. Key sections include a home page with my portrait and a short introduction, plus an about page detailing my educational and professional background. Custom CSS styling is applied via a `styles.css` file.
## Installation

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

2. **Install Quarto:**
   Download and install Quarto by following [the official Quarto installation guide](https://quarto.org/docs/get-started/).

3. **Serve the Website Locally:**
   Run the following command to preview locally:
   ```bash
   quarto preview
   ```

4. **Build the Website:**
   Use the following command to build the site to static HTML files:
   ```bash
   quarto render
   ```

## Project Structure

This repository is structured as follows:

```plaintext
.
├── _quarto.yml              # Configuration file for Quarto project settings
├── index.qmd                # Home page
├── about.qmd                # About page
├── analysis.qmd             # Basic Data Analysis satisfying project requirement 2.3
├── styles.css               # Custom CSS adjustments
├── resources/
│   └── portrait.jpg         # personal portrait displayed on the homepage
└── README.md                # Project README documentation
```

## Usage

1. **Modify Content:**
   - Update `index.qmd`, `about.qmd`, and `analysis.qmd` to change the webpage text and content as needed.
2. **Customize Styles:**
   - Modify `styles.css` to adjust css elements.
3. **Run Locally or Deploy:**
   - Use `quarto preview` for local viewing and `quarto publish` for deployment.

## Customization
- **Theme and Styles:**
  - The website uses the "morph" theme by default. This can be changed in `_quarto.yml` under `format -> html -> theme`.
  - Additional style customizations are defined in `styles.css` (e.g., layout, font size, and image presentation).

- **Adding Pages:**
  - To add more pages, create new `.qmd` files and add them to `_quarto.yml` under the navbar section.

## File Overview

### 1. `_quarto.yml`
Config file defining the overall structure, layout, and styling options for the website.

### 2. `index.qmd`
Main landing page for the website.

### 3. `about.qmd`
Provides a detailed biography and professional summary.
  
### 4. `styles.css`

Custom CSS file defining small customizations related to website's style:
- **Main Layout**: Centers main elements on the page with flexbox.
- **Hero Image**: Displays a circular, centered profile image on the homepage.

### 5. `resources/portrait.jpg`

The image file displayed on the homepage.
