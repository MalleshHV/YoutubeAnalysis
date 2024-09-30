# YouTube Trending Videos Analysis - Indian Videos

## Overview
This project analyzes trending YouTube videos in India using the YouTube Data API. The analysis focuses on various metrics such as views, likes, comments, title lengths, and more to understand the factors that contribute to a video becoming trending.

## Goals of the Analysis
1. **Total Views**: Calculate the total number of views for trending videos.
2. **View Distribution**: Analyze if having many views is a requirement for a video to trend.
3. **Likes and Comments**: Investigate the same questions for likes and comment counts.
4. **Longest Trending Video**: Identify which video remained the longest on the trending list.
5. **Capitalized Words**: Count how many trending videos have fully capitalized words in their titles.
6. **Title Lengths**: Analyze the lengths of trending video titles and their relationship to trending status.
7. **Correlation Analysis**: Examine correlations between views, likes, dislikes, comment counts, title lengths, and other attributes.
8. **Common Words**: Identify the most common words in trending video titles.
9. **Top Channels**: Determine which YouTube channels have the largest number of trending videos.
10. **Video Categories**: Find out which video category has the largest number of trending videos.
11. **Publishing Patterns**: Analyze when trending videos were published, including days of the week and times of day.

## Requirements
To run this analysis, you will need:
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `google-api-python-client`, `nltk`
- A valid YouTube Data API key


## Installation Instructions
To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MalleshHV/YoutubeAnalysis.git
   cd YoutubeAnalysis

2. **Install Required Libraries**
   ```bash
   pip install pandas matplotlib seaborn google-api-python-client nltk


## Usage

1. Replace the placeholder API key in the code with your actual YouTube Data API key.
2. Run the Jupyter Notebook `Youtube_API.ipynb` to execute the analysis. The notebook contains all the necessary code to fetch data and perform the analysis.
3. The results will be displayed as output and visualizations throughout the notebook.

## Data Analysis Steps

1. **Fetch Trending Videos**: Use the YouTube Data API to retrieve trending videos in India.
2. **Data Processing**: Extract relevant metrics such as views, likes, comments, and title lengths.
3. **Statistical Analysis**: Compute summary statistics and visualize distributions for views, likes, comments, and title lengths.
4. **Correlation Analysis**: Generate a correlation matrix to understand relationships between different metrics.
5. **Text Analysis**: Identify common words in video titles and count fully capitalized words.
6. **Channel and Category Analysis**: Count trending videos by channel and category.
7. **Publishing Time Analysis**: Analyze the publish dates and times of trending videos.


## Results

The analysis provides insights into the characteristics of trending videos in India, helping content creators and marketers understand what makes a video successful.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [YouTube Data API](https://developers.google.com/youtube/v3)
- [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/) for data analysis and visualization.
- [NLTK](https://www.nltk.org/) for natural language processing.



## Contact

For any questions or feedback, please contact at hvmallesh1218@gmail.com.
