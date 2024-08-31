# User Segmentation Analysis in the Trash to Treasure Mobile Application

## Overview

This project focuses on the segmentation and profiling of users using K-Means clustering. The analysis is based on user interactions with the mobile application "Trash to Treasure," a platform where users can post ads to sell items they no longer need. The main goal of this analysis is to segment users based on their behavior in the app and to test statistical hypotheses related to key product metrics.

## Table of Contents

- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusions and Recommendations](#conclusions-and-recommendations)
- [License](#license)

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for analysis.
- `notebooks/`: Jupyter Notebooks with the code for data analysis and clustering.
- `results/`: Output files including visualizations and clustering results.
- `README.md`: Project overview and instructions.

## Data Description

The dataset includes user interaction data with various events captured within the mobile application. Key features include:

- `user.id`: Unique identifier for each user.
- `event.name`: Name of the event triggered by the user (e.g., `tips_show`, `photos_show`, `advert_open`).
- `timestamp`: The time when the event occurred.

## Methodology

1. **Data Preprocessing**: 
   - Cleaning and normalizing the data to prepare it for clustering.
   - Scaling features to ensure they contribute equally to the clustering process.

2. **K-Means Clustering****: 
   - Applied the elbow and silhouette methods to determine the optimal number of clusters.
   - Performed K-Means clustering on the preprocessed data.

3. **Cluster Profiling**: 
   - Analyzed the characteristics of each cluster, including the frequency of events and user behaviors.

## Results

- **Optimal Clusters**: Based on the elbow and silhouette methods, the optimal number of clusters was determined to be 3.
- **Cluster Distribution**: The clusters exhibit distinct behaviors, with differences in event interaction frequencies and user retention patterns.

## Conclusions and Recommendations

### Key Findings

- **User Retention**: Identified specific user groups that are more engaged and have higher retention rates.
- **Event Interaction**: Certain events, such as `contacts_show`, have a significant impact on user retention.

### Recommendations

1. **Implement Personalized Retention Strategies**:
   - Tailor retention efforts to each cluster, focusing on the most engaged users.

2. **Continue Monitoring Key Metrics**:
   - Regularly track metrics like retention rate and event frequency to adapt strategies as needed.

3. **Conduct Further Studies**:
   - Perform additional research to gain deeper insights into user preferences and improve the app experience.

4. **Enhance User Experience**:
   - Optimize the app interface based on user behavior patterns observed.

5. **Explore New Acquisition Channels**:
   - Evaluate new user acquisition sources to improve overall retention and engagement.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/BarbOrt/Segmentacion-de-Usuarios-en-Aplicaciones-Moviles/blob/main/LICENSE.txt) file for details.


