# World Economic Classification

## Project Overview
The goal of this project is to identify which features most significantly influence Gross Domestic Product (GDP) using statistical analysis. By exploring various economic indicators and employing machine learning models, this project aims to provide insights into the key drivers of economic performance across different countries.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Analysis Workflow](#analysis-workflow)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/lgib88/World-Economic-Classification.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd World-Economic-Classification
    ```
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Prepare your data:**
   - Ensure your dataset is placed in the `data` folder. The dataset should include various economic indicators for multiple countries.

2. **Run Jupyter notebooks:**
   - Use the notebooks in the `notebooks` folder to perform exploratory data analysis (EDA) and build statistical models.
   - For example, start with `EDA.ipynb` to understand the data distribution and relationships between features.

3. **Execute Python scripts:**
   - Additional analysis and model training can be performed using the scripts in the `scripts` folder. For instance, run `model_training.py` to train and evaluate machine learning models.

## Project Structure
- `data/`: Contains the datasets used for analysis.
- `notebooks/`: Jupyter notebooks for EDA and statistical modeling.
  - `EDA.ipynb`: Exploratory Data Analysis.
  - `Feature_Engineering.ipynb`: Feature creation and transformation.
  - `Model_Training.ipynb`: Training machine learning models.
- `scripts/`: Python scripts for data processing and analysis.
  - `data_cleaning.py`: Script to clean and preprocess data.
  - `model_training.py`: Script to train and evaluate models.
- `slides/`: Presentation slides summarizing the project's findings.
- `.gitignore`: Specifies files to ignore in the repository.
- `README.md`: Project documentation.
- `requirements.txt`: Python dependencies required for the project.

## Data Sources
The datasets used in this project are sourced from reputable economic databases such as the World Bank, International Monetary Fund (IMF), and other reliable sources. Detailed information about the datasets and their sources can be found in the `data` folder.

## Analysis Workflow
1. **Data Collection and Cleaning:**
   - Gather datasets from various sources.
   - Clean and preprocess the data using scripts in the `scripts` folder.

2. **Exploratory Data Analysis (EDA):**
   - Use `EDA.ipynb` to visualize data distributions and relationships.

3. **Feature Engineering:**
   - Create and transform features using `Feature_Engineering.ipynb`.

4. **Model Training:**
   - Train and evaluate machine learning models with `Model_Training.ipynb`.

5. **Result Interpretation:**
   - Analyze model results to identify key economic indicators influencing GDP.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes. Ensure your code adheres to the project's coding standards and includes relevant tests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

For more information, visit the [GitHub repository](https://github.com/lgib88/World-Economic-Classification).