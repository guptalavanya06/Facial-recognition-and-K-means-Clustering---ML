# Facial-recognition-and-K-means-Clustering---ML
Jupyter Notebook implementation for detecting faces in an image and clustering (K-Means) them into two groups based on color features (hue and saturation). A template face image is also added to determine which cluster it belongs to.

Aim
The aim of this project is to detect faces in an image and group them based on visual similarity. The project focuses on extracting basic colour features from each detected face and using them to cluster similar faces into groups. It also includes checking where a new template face fits among these groups and visualizing the results through graphs. 
The output includes a scatter plot that shows the clustered faces, the centroids of each cluster, and the template face placed on the graph for visual verification and comparison.

Methodology
Face Detection
•	Detect faces using Haar Cascade in OpenCV and draw rectangles around detected faces
Feature Extraction
•	Convert faces to HSV color space and calculate average hue and saturation
Clustering
•	Apply K-Means clustering (k = 2) to group similar faces together
Template Classification
•	Extract features from a template face and predict which cluster it belongs to
Visualization
•	Plot hue vs saturation scatter graph, showing clusters, centroids and the template face on the graph. 

Key Findings
•	Faces with similar visual color features are grouped into the same cluster.
•	The clustering method successfully separates faces into meaningful groups.
•	The scatter plot clearly shows how faces with similar features lie close to each other.
•	The template face is correctly matched with the most similar cluster.
•	Visualization makes it easier to understand the clustering results.

Conclusion
This project demonstrates that simple feature extraction and clustering methods can be used to organize facial images based on similarity. The results highlight how basic machine learning techniques can reveal patterns in visual data and support comparison between images. Such approaches can serve as a foundation for more advanced image analysis and recognition systems.

