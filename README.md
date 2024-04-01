# Description:
AcademicTrendAnalyzer is a project aimed at harnessing natural language processing (NLP) to extract insights from academic theses. This tool is particularly focused on theses written in French, analyzing their content to classify them into research domains, detect trends, and provide a comprehensive overview of academic research trajectories over time.

# Tasks:
## Data Preprocessing: Normalizes establishment names, filters the dataset for French-language theses, and cleans the data to remove entries with missing information in critical fields.
## NLP Analysis: Uses spaCy to process the text of each thesis, extracting linguistic features and performing entity recognition to classify theses into research domains and identify key trends.
## Insight Extraction: Aggregates the processed data to highlight patterns in academic research over time, such as shifts in popular research topics, the evolution of certain fields, and correlations between different areas of study.


# Dataset:
The project utilizes a curated dataset of academic theses from Paris Dauphine University, encompassing several key attributes:

Titre (Title): The French title of the thesis.
Résumé (Abstract): A brief summary of the thesis in French.
Année (Year of Defense): The year the thesis was defended.
Genre (Field of Study): The academic discipline or field of study.
Code_etab (Establishment Code): A unique identifier for the academic establishment, which has been normalized to account for naming inconsistencies (e.g., "Paris 1" and "Sorbonne Université" are treated as equivalent).


# Tools and Technologies
Python: The primary programming language used for data manipulation and running NLP pipelines.
spaCy: A powerful library for advanced natural language processing, used for tasks like tokenization, part-of-speech tagging, named entity recognition, and more, to analyze the text data within the theses.
Pandas: Employed for data preprocessing, including filtering for French-language theses, handling missing values, and normalizing establishment names to ensure data consistency.
