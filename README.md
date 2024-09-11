# The Silk Road - Career Path Prediction

The Silk Road is an AI-driven mobile application designed to guide developers and software engineers through their professional journey. This project provides personalized learning paths and career track recommendations based on users' skill levels, interests, and career goals. The app uses AI models to predict suitable career paths and suggest learning resources.

## Features

- **Personalized Career Path Prediction**: Based on user data and preferences, predict a suitable career path for each individual. The AI model analyzes user interactions within the app, such as skills, interests, and learning progress, to suggest the most aligned career path.
- **Learning Resource Recommendations**: Provide tailored learning materials to help users grow in their chosen career track.

## Dataset Overview

- **Dataset Name**: `Indeed_10k.csv`
- **Description**: This dataset contains job listings from Indeed, including job titles, companies, locations, ratings, job summaries, and required skills.
  - Columns include:
    - `Name`: Job title (e.g., Software Engineer, Junior Developer)
    - `Company`: The company offering the job
    - `City`: The location of the job
    - `Ratings`: Optional rating for the company
    - `Summary`: A brief description of the job responsibilities
    - `Skills`: Key skills required for the job (e.g., Python, Java, C++, SQL)
    - `Date`: When the job was posted

## Jupyter Notebook: `Career_path.ipynb`

This notebook contains the code for data analysis and AI model training, designed to predict the most suitable career paths based on user data. It includes the following steps:

1. **Data Preprocessing**: Cleaning and organizing the dataset for model training.
2. **Feature Engineering**: Extracting important features from the dataset such as skills and interests.
3. **Model Training**: Implementing and training a machine learning model (e.g., decision trees, neural networks) to predict the career path.
4. **Evaluation**: Assessing the accuracy and performance of the model.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- Scikit-learn
- TensorFlow/Keras

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/YousefElgamily/the-silk-road.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook Career_path.ipynb
    ```

## How to Use

1. **Data Preparation**: The dataset `Indeed_10k.csv` is used to train the model. Ensure that it is located in the correct directory.
2. **Run the Model**: Use the Jupyter Notebook to execute the code and generate career path predictions.
3. **Customization**: You can modify the questions and features used for predictions to fit your specific requirements.

## Contribution

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License

## Author

 Yousef Elgamily
