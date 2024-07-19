# Steam-Games-Data-Analysis-and-Recommendation-System-with-PySpark-and-MLflow

This project involves loading, analyzing, and building a recommendation system based on Steam games data using PySpark and MLlib. The data includes details about games played, user behavior, and hours played.

## Table of Contents

- [Project Structure](#project-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project contains a Jupyter Notebook with the following main sections:

1. **Loading Libraries**: Importing essential libraries such as PySpark's `SparkSession`, MLlib, Seaborn, and Matplotlib.
2. **Loading Datasets**: Loading data from the Databricks File System (DBFS).
3. **Data Analysis and Visualization**: Analyzing and visualizing the data using tools like Seaborn and Matplotlib.
4. **Building the Recommendation System**: Developing a recommendation model using the Alternating Least Squares (ALS) algorithm from PySpark's MLlib.

## Setup

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/steam-games-analysis.git
    cd steam-games-analysis
    ```

2. **Install Dependencies**:
    Ensure you have PySpark and MLflow installed. You can use the following commands to install them:
    ```sh
    pip install pyspark
    pip install mlflow
    ```

3. **Run the Jupyter Notebook**:
    Open the notebook `Steam_Games_ARS_ml.ipynb` using Jupyter:
    ```sh
    jupyter notebook Steam_Games_ARS_ml.ipynb
    ```

## Usage

1. **Run the Notebook**:
    - Open the notebook in your Jupyter environment and run all cells to execute the data analysis and recommendation system building processes.
    - Modify the file paths and names as needed for your specific datasets.

2. **Adapt Functions for Your Needs**:
    - The data loading and preprocessing steps can be adapted to handle different datasets or perform additional processing steps as required.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

1. **Fork the Project** on GitHub.
2. **Create a Feature Branch** (`git checkout -b feature/AmazingFeature`).
3. **Commit Your Changes** (`git commit -m 'Add some AmazingFeature'`).
4. **Push to the Branch** (`git push origin feature/AmazingFeature`).
5. **Open a Pull Request**.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
