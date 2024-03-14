
# King County Housing Data EDA Project for Jacob Phillips

search This repository is dedicated to a comprehensive Exploratory Data Analysis (EDA) of the King County Housing Data. The primary objective of this project is to assist Jacob Phillips in his research to find the ideal historic house. Specifically, we aim to answer the research question: How can we identify historic houses with 4 or more bathrooms and large lots suitable for installing a tennis court and/or pool, located near golfing amenities, and not situated on waterfronts, in the Seattle area?

## Project Objective

To support Jacob Phillips in his search for a unique property that meets his specific criteria:
- Historic houses with a minimum of 4 bathrooms.
- Large lots that can accommodate a tennis court and/or pool.
- Proximity to golfing amenities.
- Not located on waterfronts.

## Hypotheses

The analysis will test the following hypotheses to guide Jacob Phillips in his decision-making process:

1. **Historic houses are more likely to have larger lots**, which could accommodate Jacob's desire for a tennis court and/or pool. 

2. **Areas with lower average lot sizes might have a higher density of houses**, potentially increasing the likelihood of finding two adjacent properties for sale. 

3. **Historic houses with recent renovations are more likely to meet modern standards**, including the desired number of bathrooms.

## Methodology

- Data acquisition from PostgreSQL database.
- Data cleaning and preprocessing to ensure accuracy and relevancy.
- Exploratory Data Analysis to uncover patterns, trends, and anomalies within the dataset.
- Testing of hypotheses through statistical methods and data visualization techniques.

## Project Folder Structure

- **EDA.ipynb**: The main Jupyter Notebook containing the exploratory data analysis.
- **data/**: Directory containing the dataset used in this analysis.
- **.env**: An environment file containing database connection credentials (Note: This file should not be uploaded to GitHub for security reasons).
- **requirements.txt**: A list of Python packages required to run the notebook.

## Requirements

Before running the notebook, ensure you have Python 3.11.3 installed on your system. This project also requires PostgreSQL for data retrieval.

## Setup

### Virtual Environment

Create a virtual environment and install the required Python packages using the following commands:

```bash
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### Node.js for Plotly

If you intend to use Plotly in Jupyter Lab, make sure Node.js is installed:

```bash
node -v
```

If Node.js is not installed, follow the installation instructions provided in the original README.md file for your operating system.

## Running the Notebook

With the environment set up and activated, launch Jupyter Lab:

```bash
jupyter lab
```

Navigate to the `EDA.ipynb` notebook and run the cells to perform the exploratory data analysis.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional analyses.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
