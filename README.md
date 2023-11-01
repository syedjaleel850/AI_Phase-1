# Fake News Detection Using NLP

Fake news, misinformation, and disinformation are growing concerns in the digital age. They spread rapidly through social media and other online channels, potentially leading to misinformation, confusion, and even real-world consequences. Natural Language Processing (NLP) techniques can play a crucial role in identifying and combating fake news.

In this project, we used the BERT algorithm to train our model, achieving an impressive accuracy of 99.95% in identifying fake news.


## Dependencies

The project relies on the following libraries and dependencies:

- [matplotlib](https://matplotlib.org/): A Python plotting library for creating visualizations.

- [pandas](https://pandas.pydata.org/): A data manipulation and analysis library.

- [nltk (Natural Language Toolkit)](https://www.nltk.org/): A comprehensive library for natural language processing.

- [scikit-learn](https://scikit-learn.org/stable/): A machine learning library for various tasks, such as feature extraction and model training.

- [NumPy](https://numpy.org/): A library for numerical computations in Python.

- [TensorFlow](https://www.tensorflow.org/): An open-source machine learning framework developed by Google.

- [Transformers](https://huggingface.co/transformers/): A library for natural language understanding using state-of-the-art models.

It's strongly recommended to use Python 3 to execute project and ensure that you have a Python 3.x version (3.5 or newer) installed to run your code effectively

### Python Packages

You can install the Python packages listed above using `pip` with the following command:

pip install matplotlib pandas nltk scikit-learn numpy tensorflow transformers

Upgrade the pip version to 23.3.1, as older versions may not be able to install the Transformers package.

pip install --upgrade pip

## Installation

Install all the packages using pip command pip package_name

# Clone the repository

git clone https://github.com/PrNirmal/Naan-Mudhalvan.git

# Change to the project directory
cd Naan-Mudhalvan

## Environment Used

This program can be executed on various platforms and development environments.The following are the environments used during the project development:

- **Jupyter Notebook**: You can run the code in a Jupyter Notebook for interactive data analysis and visualization.

- **PyCharm**: PyCharm is a popular integrated development environment (IDE) for Python. You can use it for writing, debugging, and running your Python code.

- **Visual Studio Code (VSCode)**: VSCode is a versatile code editor that supports Python and offers extensions for enhanced Python development.

Make sure to set up your chosen environment and install the necessary dependencies as described in this above before running the program.

## Dataset

In this project, we used two CSV files containing a dataset of news articles. The dataset consists of one file with fake news (Fake.csv) and another with real news (True.csv). These files contain the following attributes: 'Title', 'Text', 'Subject', and 'Date'.

The dataset was preprocessed, features were extracted, and fake and real news articles were concatenated. A label attribute was added to identify the type of news, with '0' for fake news and '1' for real news.

### Source

The dataset used in this project was obtained from Kaggle. You can find the original dataset [here](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset).

### Data Split

The data was divided into the following sets for training, validation, and testing:

- Training set: 35,918 records
- Validation set: 4,490 records
- Test set: 4,490 records
