# Indian Startup Funding Dashboard

## Overview

The **Indian Startup Funding Dashboard** is a data-driven project designed to analyze and visualize the funding landscape of Indian startups. Built entirely in Python, this dashboard enables users to explore trends, discover key insights, and better understand the startup ecosystem in India by leveraging interactive visualizations.

## Features

- **Comprehensive Data Analysis:** Explore the funding amounts, rounds, investors, and startup categories.
- **Interactive Visualizations:** Gain insights through charts and graphs generated with Python libraries.
- **Trend Identification:** Track funding trends over time, by sector, and by region.
- **User-Friendly Dashboard:** Intuitive interface for users to filter and interact with the dataset.

## Technologies Used

- **Python** (100%)
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Dashboard: `streamlit` 
  - Data Source: CSV/Excel files (startup funding data)

## Getting Started

### Prerequisites

- Python 3.7+
- Recommended: Create and activate a virtual environment

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Saamiyah26/Indian-Startup-Funding-Dashboard.git
   cd Indian-Startup-Funding-Dashboard
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Prepare the dataset:**  
   Ensure your startup funding dataset (CSV/Excel) is placed in the project directory or update the script with the correct path.

2. **Run the dashboard:**
   - If using **Streamlit**:
     ```bash
     streamlit run app.py
     ```
   - If using **Dash**, run:
     ```bash
     python app.py
     ```

3. **Interact with the dashboard:**  
   Open the provided local URL in your browser and explore the visualizations.

## Project Structure

```
Indian-Startup-Funding-Dashboard/
├── app.py                 # Main dashboard script
├── data/                  # Data files (CSV/Excel)
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For questions, suggestions, or collaboration, feel free to open an Issue or reach out via [GitHub](https://github.com/Saamiyah26).
