# UoW_Data_Engineering
Here's the updated README file with details for Week 9 added:
________________________________________
Tutorial Weeks 7–9: Unstructured Data Exploration, Preprocessing, and Storage
This repository contains materials and solutions for Weeks 7, 8, and 9 of the 5DATA005C Data Engineering module. These tutorials cover the exploration, preprocessing, and storage of unstructured data, specifically image and text data, using Python, MongoDB, and Google Colab.
________________________________________

Week 7: Unstructured Data Exploration
Topics Covered
1.	Image Data Exploration:
o	Investigate basic image properties (format, size, and mode).
o	Extract metadata using EXIF.
o	Visualize pixel distributions through histograms.
o	Compute image statistics (mean, median, mode).
o	Perform extra exercises involving analysis of multiple images.
2.	Text Data Exploration:
o	Examine textual properties (length, word count, specific content).
o	Visualize word distributions using word count and word clouds.
o	Additional exercises for analyzing and visualizing multiple documents.
________________________________________

Week 8: Unstructured Data Preprocessing
Topics Covered
1.	Image Preprocessing:
o	Transformations: Resize, rotate, and denoise images individually and in sequence.
o	Feature Extraction: 
	Mean and norm intensity.
	Shape features (area, perimeter, centroid, bounding box).
	Combine extracted features into metadata files.
o	Annotation: Save metadata as JSON for image features.
2.	Text Preprocessing:
o	Preprocessing Techniques: 
	Text normalization, tokenization, punctuation removal, stop word removal.
	Stemming and lemmatization.
o	Vectorization: 
	Represent text numerically using Bag of Words (BoW) and TF-IDF.
o	Metadata Creation: 
	Explain vectorization and label processed text data.
	Save metadata as a JSON file.
________________________________________

Week 9: Unstructured Data Storage
Topics Covered
1.	MongoDB Basics:
o	Set up MongoDB Atlas, create clusters, and configure access.
o	Use pymongo to connect to MongoDB from Google Colab.
2.	Image Data Storage:
o	Create a CBIR database with collections for: 
	Processed images.
	Image metadata.
o	Store and query image metadata and processed images.
3.	Text Data Storage:
o	Create an NLP database with collections for: 
	Processed documents.
	Document metadata.
o	Store and query text metadata and processed documents.
4.	Extra Activities:
o	Extend texture extraction techniques from Week 8 (e.g., GLCM features like contrast and dissimilarity).

