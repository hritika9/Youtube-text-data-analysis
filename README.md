# Youtube Text Data Analysis using Python

### Table of Contents
 - [Project Overview](Project-Overview)
 - [Data Sources](Data-Sources)
 - [Data Extraction/Cleaning](Data-Extraction/Cleaning)
 - [Exploratory Data Analysis](Exploratory-Data-Analysis)
 - [Results](Results)
 - [Recommendations](Recommendations)
 - [Limitations](Limitations)
 - [Tools and Libraries](Tools-and-Libraries)


### Project Overview

This project focuses on analyzing textual data from YouTube videos, including video titles, descriptions, and comments. The aim is to uncover insights such as common themes, sentiment analysis,wordcloud analysis and emoji analysis. This analysis can provide valuable information for content creators, marketers, and researchers interested in understanding audience engagement and content trends on YouTube.

### Data Sources

- Python -Jupyter notebook

### Data Extraction/Cleaning

1. Extracted data from 'UScomments.csv' file using pandas library
2. Handle missing or duplicate data.

### Exploratory Data Analysis

EDA involves answering  key questions such as:

- Top most used emoji in the comments

  ![newplot](https://github.com/hritika9/Youtube-text-data-analysis/assets/94508484/50d741b0-f27d-466b-8c8a-20356870c35d)

- Number of postive and negative comments.
- Analysing most liked category.
- Find out whether audience is engaged or not.
- Which channel has the largest number of trending videos.
- Does punctuation in title have any relation with views , likes ,dislikes and comments?



### Results

The analysis result are summarized as follows:

- Top five emoji's mostly used by audience
- Common Positive Words: The most frequently used positive words included "love," "great," "amazing," "awesome," "fantastic," and "excellent."
    - Insights: These words indicate a strong positive reception and high levels of audience appreciation for the content.
- Common Negative Words: Frequently used negative words included "bad," "hate," "dislike," "terrible," "awful," and "poor."
     - Insights: The negative words suggest specific areas of discontent or criticism from the audience.
- Categories such as "Entertainment," "Music," and "Gaming" had the highest number of likes.
- The higher the number of views the more likes that video has.

### Recommendations

1. Focus on High Engagement Categories: Content creators should prioritize categories like "Entertainment," "Music," and "Gaming" for higher engagement and audience reach.
2. Effective Title Crafting: Utilizing punctuation such as exclamation marks, question marks, and ellipses in video titles can enhance appeal and increase likes and views. Content creators should experiment with different title formats to see what resonates best with their audience.

### Limitations

Found many missing data , had to delete those rows.

### Tools and Libraries

- Python: The main programming language used for the project.
- pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- TextBlob: For sentiment analysis.
- Matplotlib and Seaborn: For data visualization.
- WordCloud: For creating word clouds.
- emoji: For emoji analysis
- string: for analysis the effect the use punctuation in title on likes and views


