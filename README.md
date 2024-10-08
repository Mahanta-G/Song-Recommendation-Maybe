# Song Recommendation System

## Overview
This project implements a content-based song recommendation system that suggests songs based on the similarity of their lyrics. The core algorithm utilizes TF-IDF (Term Frequency-Inverse Document Frequency) to analyze song lyrics, and cosine similarity to find similar songs.

## Features
- **Content-Based Recommendations:** Recommends songs based on lyrics similarity.
- **Scalability:** Designed to handle a dataset with up to 50,000 songs.
- **Flexible Input:** Users can input any song title to receive personalized recommendations.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Scipy

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Mahanta-G/Song-Recommendation-Maybe-.git
   cd Song-Recommendation-Maybe-
   ```
2. Install the required packages:
   ```bash
   pip install pandas numpy scikit-learn
   ```

## Dataset
The dataset should be a CSV file containing the following columns:
- **artist:** The name of the artist.
- **song:** The title of the song.
- **text:** The lyrics of the song.

You can replace the dataset path in the code to point to your CSV file.

## Usage
1. Run the main script:
   ```bash
   python main.py
   ```
2. Follow the prompts to enter a song name and the desired number of recommendations.

## Example
```
Enter a song name: Smoke On The Water
Enter the number of recommendations you want: 5
Recommended songs for 'Smoke On The Water':
Recommendation 1: 
Song: Highway Star | Artist: Deep Purple | Similarity Score: 0.85
-------------
Recommendation 2: 
Song: Child in Time | Artist: Deep Purple | Similarity Score: 0.82
-------------
...
```

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue.

## Acknowledgements
- Inspired by various music recommendation systems and algorithms.
- Thanks to all the contributors and resources that helped in building this project.
