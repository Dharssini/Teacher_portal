## Digital portal - Assignment plagiarism detector

## Live Tool

You can access the live tool at 

## Requirements

To run this app locally, you will need to install the following libraries:
- streamlit
- matplotlib
- networkx
- python-docx
- scikit-learn
- pandas


While utilizing the live tool, the server temporarily stores uploaded files while the app processes them. Once the analysis is finished and the results are displayed, the files are eliminated from the server. The speedy performance of the tool when comparing large groups of files can be attributed to the efficient algorithms implemented by the app. For example, the TF-IDF algorithm assigns a weight to each word in the document based on its importance, thereby enabling the app to precisely gauge the similarity between different files without having to compare every single word. Furthermore, the app utilizes the cosine similarity metric, which is a swift and effective method to compare the similarity between pairs of documents.


