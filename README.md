This repository contains the frontend and backend design of a Movie Review Q&A Assistant, created to provide an interactive platform where users can ask questions about a movie and receive answers based on user reviews. The system processes and extracts key information from movie reviews to deliver concise, relevant answers to user queries.

Features
Review Import: Allows users to upload movie review datasets (e.g., IMDb sample reviews).
Text Preprocessing: Automatically cleans the reviews by stripping HTML tags and removing unnecessary punctuation.
Keyword Extraction: Extracts important keywords from reviews for better question answering.
Q&A Interface: Users can ask specific questions about a movie, and the system will provide relevant answers based on the review content.
Review Analysis: Offers insights into the sentiment and key details found within the review texts.
Concise Answers: The system generates clear, concise answers to user queries.
System Design
The system is designed to be:

Responsive: Optimized for desktops, tablets, and mobile devices, ensuring accessibility and a smooth user experience across different screen sizes.
Fast and Efficient: Processes the review data quickly, providing fast response times with optimized code and handling.
User-Friendly: The interface is simple and intuitive, enabling users to easily interact with the system and get the information they need.
Technologies Used
Python: Used for the backend processing and handling of movie review data.
Natural Language Processing (NLP): Libraries like nltk and spaCy are used for text cleaning and keyword extraction from the reviews.
Transformers: Employed to implement the Retrieval-Augmented Generation (RAG) model, which helps generate answers from the review data.
Pandas: Used for handling and processing the CSV files containing the movie reviews.
