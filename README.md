# Book_Rec

## Overview

This project is a Machine Learning and AI-based Book Recommendation System developed in Python. The system leverages collaborative filtering and content-based filtering to provide personalized book recommendations to users. It uses various libraries and tools in Python to preprocess data, train models, and generate recommendations.

## Features

- Collaborative Filtering: Recommends books based on user-user and item-item similarity.
- Content-Based Filtering: Recommends books based on the features of the books and user preferences.
- Hybrid Approach: Combines both collaborative and content-based filtering to enhance recommendation accuracy.
- Interactive User Interface: Allows users to input their favorite book and receive recommendations.
- Scalable and Efficient: Designed to handle large datasets and provide real-time recommendations.

## Installation

### Prerequisites

- Python 3.7+
- pip

### Libraries

The required Python libraries can be installed using the following command:

```bash
pip install -r requirements.txt
```

### Requirements File (`requirements.txt`)

```
numpy
pandas
scikit-learn
```

## Dataset

The project uses a book dataset which should contain information such as book titles, authors, genres, and user ratings. An example dataset is provided in the directory.

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/Recommendation-System.git
    cd Recommendation-System
    ```

2. **Prepare the dataset:**

    Ensure that your dataset is in the `data` directory. The dataset should be in CSV format and contain columns for user IDs, book IDs, ratings, and book metadata.

3. **Train the models:**

    Run the script to train the recommendation models:

    ```bash
    python train_models.py
    ```

4. **Start the web application:**

    Run the Flask application to start the web server:

    ```bash
    python app.py
    ```

5. **Access the application:**

    Open your web browser and go to `http:` to access the book recommendation system.

## Project Structure

```
book-recommendation-system/
│
├── app.py                    # Flask application
├── Model.py           # Script to train recommendation models
├── data/
│   ├── books.csv             # Book dataset
├── static/
│   └── css/                  # CSS files for the web app
├── templates/
│   └── index.html            # HTML template for the web app
├── requirements.txt          # Python dependencies
└── README.md                 # Project README
```


## Acknowledgments

- [scikit-learn](https://scikit-learn.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)

## Contact

For any questions or suggestions, please contact jiamohan@gmail.com or jarredperos@gmail.com or create an issue in this repository.

---

Feel free to modify this README to better suit the specifics of your project.
