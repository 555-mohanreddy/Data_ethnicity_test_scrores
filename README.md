

# Test Score Insights

Welcome to the repository for my project on analyzing test scores among different ethnicities using Tableau, MySQL, and Python. This project showcases how to create a comprehensive Tableau dashboard for analyzing trends and key performance indicators (KPIs) related to test scores.

## Table of Contents

1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Project Overview](#project-overview)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

This project involves creating a Tableau dashboard to analyze the sales trend of a dataset comprising various test scores among ethnicities. The goal is to provide clear insights into key performance indicators (KPIs) such as the comparison between reading, math, and writing scores, and performance among different ethnicity groups. Additionally, the project highlights areas needing improvement through dynamic profit target slicers.

## Technologies Used

- **Tableau**: For data visualization and dashboard creation.
- **MySQL**: For data storage and management.
- **Python**: For data transformation and cleaning using Jupyter Notebook.

## Project Overview

### 1. Tableau Dashboard
   - Created a Tableau dashboard analyzing the sales trend of different test scores among ethnicities.
   - The dashboard effectively displays trends in test scores and provides clear insights into KPIs such as the comparison between reading, math, and writing scores, and performance among different ethnicity groups.
   - Identified areas of improvement needed through flexible and dynamic profit target slicers, highlighting problematic markets for reassessment.

### 2. Data Preparation
   - Uploaded the dataset into a MySQL server.
   - Transformed and cleaned the data using Python in Jupyter Notebook.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/test-score-insights.git
    cd test-score-insights
    ```

2. **Set up MySQL**
    - Install and set up [MySQL](https://dev.mysql.com/downloads/).
    - Import the dataset into the MySQL server using the provided SQL script.

3. **Set up Python environment**
    - Create a virtual environment and activate it:
      ```bash
      python -m venv env
      source env/bin/activate  # On Windows use `env\Scripts\activate`
      ```

    - Install required Python packages:
      ```bash
      pip install -r requirements.txt
      ```

4. **Set up Jupyter Notebook**
    - Launch Jupyter Notebook to transform and clean the data:
      ```bash
      jupyter notebook
      ```

## Usage

1. **Data Cleaning and Transformation**
   - Open the Jupyter Notebook `data_cleaning.ipynb` and run the cells to clean and transform the data.

2. **Uploading Data to MySQL**
   - Ensure the MySQL server is running and execute the SQL script to upload the cleaned data.

3. **Tableau Dashboard**
   - Open Tableau and connect to the MySQL database.
   - Import the data and create visualizations as demonstrated in the project files.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the existing style and passes all tests.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact me at [dubbamohan55@gmail.com].
