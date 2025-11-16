# ICA Report Project

This repository contains the source code for the "ICA Report Project," a website generated using Quarto. This project aims to provide comprehensive documentation and insights into various aspects, including methodology, key files, and an overview of the technologies used (R, Quarto, and LaTeX).

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Building the Website](#building-the-website)
  - [Viewing Locally](#viewing-locally)
- [Contributing](#contributing)
- [License](#license)

## Overview

The "ICA Report Project" is a documentation website built with Quarto. It covers:
- **Methodology**: Detailed explanation of the approaches and procedures used.
- **Key Files**: Important files and their roles within the project.
- **Technology Insights**: Information about R, Quarto, and LaTeX, which are integral to this project.

## Technologies Used

- **Quarto**: An open-source scientific and technical publishing system built on Pandoc. It allows for creating dynamic reports, presentations, and websites from R, Python, Julia, and Observable.
- **R**: A programming language and free software environment for statistical computing and graphics.
- **LaTeX**: A high-quality typesetting system, often used for technical and scientific documentation.

## Project Structure

```
.
├── _quarto.yml          # Quarto project configuration
├── index.qmd            # Home page content
├── methodology.qmd      # Methodology section
├── key_files.qmd        # Key files section
├── about_r.qmd          # Information about R
├── about_quarto.qmd     # Information about Quarto
├── about_latex.qmd      # Information about LaTeX
├── styles.css           # Custom CSS for the website
├── img/                 # Images used in the project
│   ├── data_analysis.gif
│   └── report_generation.gif
└── _site/               # Generated website output (after rendering)
    └── ...
```

## Getting Started

### Prerequisites

To build and view this project locally, you will need:
- **Quarto CLI**: Install from [quarto.org](https://quarto.org/docs/get-started/).
- **R (optional, but recommended)**: If you plan to modify R-based content.
- **LaTeX distribution (optional)**: If you plan to work with LaTeX features.

### Building the Website

To render the Quarto website, navigate to the project root directory in your terminal and run:

```bash
quarto render
```

This will generate the static website files in the `_site` directory.

### Viewing Locally

After rendering, you can preview the website locally by opening the `_site/index.html` file in your web browser, or by running:

```bash
quarto preview
```

This will launch a local web server and open the site in your default browser.

## Contributing

For any contributions or suggestions, please refer to the [GitHub repository](https://github.com/htevilili-1991/ica_docs).

## License

This project is open-source. Please refer to the repository for specific licensing information.
