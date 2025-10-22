# Data Analysis Workflow with CI/CD

[![CI Status](https://github.com/Sharmila-Mamani/Analyze/actions/workflows/ci.yml/badge.svg)](https://github.com/Sharmila-Mamani/Analyze/actions/workflows/ci.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=flat-square)](https://Sharmila-Mamani.github.io/Analyze/)

This project establishes a robust data analysis workflow, from initial data preparation and script development to automated execution and result publishing via continuous integration and deployment (CI/CD). It involves processing an Excel dataset, correcting a critical error in the analysis script, converting the data to a more accessible format, and publishing the analysis results as JSON through GitHub Pages.

## Features

*   **Data Preparation:** Conversion of the `data.xlsx` dataset to `data.csv` for streamlined processing and version control.
*   **Script Reliability:** Identification and correction of a non-trivial error within the `execute.py` analysis script, ensuring accurate and stable data processing on specified Python and Pandas versions.
*   **Automated Linting:** Integration of `ruff` within the CI pipeline to maintain code quality and consistency.
*   **Automated Analysis:** Execution of `execute.py` in a controlled CI environment to generate up-to-date analysis results.
*   **Result Publishing:** Automatic deployment of the generated `result.json` to GitHub Pages, providing a live, accessible view of the latest analysis output.
*   **Version Control:** All source code and data (excluding generated results) are managed under Git, with CI configured to run on every push.

## Setup Instructions

To set up and run this project locally, follow these steps:

### Prerequisites

*   **Python 3.11+**: Ensure you have a compatible Python version installed.
*   **`pip`**: Python's package installer, typically included with Python installations.

### Local Installation

1.  **Clone the repository:**