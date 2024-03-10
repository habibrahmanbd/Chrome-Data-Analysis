# Chrome Data Analysis

## Overview

This project aims to analyze and visualize Chrome browser data, including browsing history, bookmarks, extensions, and more. With scripts to process and analyze various types of data exported from Chrome, this project provides insights into browsing habits, bookmark trends, and other personal browsing data analytics.

## Project Structure

The project is organized into two main directories: `data` and `src`.
```
.
├── README.md
├── data
│ ├── Chrome
│ │ ├── Addresses and more.json
│ │ ├── Bookmarks.html
│ │ ├── Device Information.json
│ │ ├── Dictionary.csv
│ │ ├── Extensions.json
│ │ ├── History.json
│ │ ├── OS Settings.json
│ │ ├── Reading List.html
│ │ └── Settings.json
│ └── tlds.csv
└── src
├── browsing_history.ipynb
└── tlds_extractor.ipynb
```

### Data

- `Chrome/`: Contains exported Chrome data in various formats (JSON, HTML, CSV).
  - `Addresses and more.json`: Information on saved addresses and other data.
  - `Bookmarks.html`: Exported bookmarks.
  - `Device Information.json`: Information about connected devices.
  - `Dictionary.csv`: Custom dictionary words.
  - `Extensions.json`: Installed Chrome extensions.
  - `History.json`: Browsing history.
  - `OS Settings.json`: Chrome OS settings.
  - `Reading List.html`: Saved reading list items.
  - `Settings.json`: Chrome browser settings.
- `tlds.csv`: List of top-level domains used for data processing.

### How to Download the Google Chrome Data
- [Download your data](https://takeout.google.com/settings/takeout) from Google Takeout.
- Extract the downloaded zip file and navigate to the `Chrome` directory to find the exported data files.

### Source Code

- `src/`: Contains Jupyter notebooks for data processing and analysis.
  - `browsing_history.ipynb`: Analyzes and visualizes browsing history data.
  - `tlds_extractor.ipynb`: Processes and extracts information from `tlds.csv`.

## Getting Started

To run the analysis scripts, ensure you have Jupyter Notebook or JupyterLab installed. You may need to install additional Python packages such as `pandas`, `numpy`, and `matplotlib` for data processing and visualization. You can install these packages using pip:

```sh
pip install jupyterlab pandas numpy matplotlib
```
Then, navigate to the src directory and launch Jupyter:

```
cd src
jupyter notebook
```
Open the `.ipynb` files to view the analyses and visualizations.

## Contributing
Contributions to the project are welcome! Whether it's adding new analyses, improving the existing notebooks, or fixing bugs, your help is appreciated. Please feel free to fork the repository and submit pull requests with your changes.

## License
This project is open source and available under the MIT License.

## Contact
For questions or suggestions, please open an issue in the GitHub repository.
Remember to replace placeholders (like `[MIT License](LICENSE)`) with actual links or information relevant to your project. This README provides a solid starting point for documenting your project and guiding users or contributors through its structure and usage.
