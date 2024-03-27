# News Article Classification Post October 7 Attack

## Introduction
This project analyzes the shift in media discourse following the Hamas attack on October 7, 2023. It examines the coverage by U.S. media outlets, especially the representation of hostages held in Gaza, to understand the informational landscape presented to the American public. Using unsupervised learning, we categorized articles into themes to explore American societal perceptions of the events compared to those in Israel.

## Dataset
We utilized a dataset comprising 7,000 U.S. news articles, filtered by the keyword "Israel" from October 7, 2023, to March 11, 2024. Attributes include title, description, content, URL, image link, publication date, and source.

## Methods
Our methodology integrated:
- **Text Normalization and Vectorization:** Using TF-IDF to capture the weight of words.
- **Clustering Techniques:** KMeans for partitioning, DBSCAN for density-based clustering, Agglomerative for hierarchical clustering, and Sentence Transformers for semantic understanding.
- **Challenges Faced:** We tackled complexities in classification quality evaluation, using silhouette scores among other metrics for analysis.

## Results
The clustering algorithms revealed insightful trends in topic coverage, with KMeans selected as the primary tool for its effectiveness in handling overlapping themes. A notable find was the sporadic coverage of the hostage topic, peaking only during key events.
![image](https://github.com/aviya-gmara/News-Classification-Project-/assets/82819879/fe00c693-834b-47f9-86cc-fd710c22018d)

## Conclusion
The project offers insights into the influence of news on public perception during war, highlighting how classification techniques can decode media focus and public interest.

## Future Work
We suggest further exploration of article patterns and expansion of the article pool to refine classification and improve metric scores.
