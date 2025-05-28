# Assingment1

## Project Setup

1.  **Clone the repository:**
    ```bash
    git clone <https://github.com/Abyaskar/Assingment1/blob/main/Assignment1.ipynb>
    ```
2.  **Place your dataset:**
    Ensure your sales dataset is named `dataset.csv` and is placed in the root directory of the project, alongside the `Assignment1.ipynb` notebook.
3.  **Install dependencies:**
    If you don't have them, install Jupyter, Pandas, and NumPy:
    ```bash
    pip install jupyter pandas numpy
    ```

## How to Run

1.  **Start Jupyter Lab or Jupyter Notebook:**
    Navigate to your project directory in the terminal and run:
    ```bash
    jupyter lab
    # OR
    jupyter notebook
    ```
2.  **Open the Notebook:**
    In the Jupyter interface that opens in your browser, click on `Assignment1.ipynb` to open it.
3.  **Run the Cells:**
    Execute each cell sequentially within the notebook to perform the data loading, cleaning, and analysis steps.

## Functionalities

The `Assignment1.ipynb` notebook performs the following data analysis tasks:

* **Data Loading:** Loads the `dataset.csv` file into a Pandas DataFrame.
* **Data Cleaning:** Identifies and handles missing values. The notebook demonstrates filling numerical missing values with the mean and categorical missing values with the mode.
* **Sales Analysis:**
    * Calculates the **sum of sales by region**.
    * Determines the **average sales per product**.
    * Identifies and displays the **highest and lowest selling products** based on average sales.
* **Numerical Statistics:** Utilizes NumPy to calculate the **mean, median, and standard deviation** for numerical fields, specifically for the 'Sales' column.

## Output

The output of the analysis will be displayed directly within the Jupyter Notebook cells as you run them. This includes:

* Initial dataset information (head, info, missing values).
* Summary of missing values before and after cleaning.
* Tabular outputs for sum of sales by region, and average sales per product.
* Lists of highest and lowest selling products.
* Calculated mean, median, and standard deviation for numerical columns.

---
