# University Students Complaint Prioritization

## Overview
The "Voices Heard" dataset is a comprehensive collection of reports and complaints submitted by students in a university setting. From academic grievances to campus safety concerns, this dataset provides valuable insights into the student experience. This project leverages Natural Language Processing (NLP) techniques to prioritize student complaints, offering valuable feedback for university administrators and educators to enhance the university experience for all students.

## Project Objectives
- **Understand Student Needs:** Use NLP to analyze complaints and identify key areas of concern among students.
- **Prioritize Issues:** Develop a model to prioritize complaints based on their content and severity.
- **Enhance Student Experience:** Provide actionable insights and recommendations to university administrators for improving the campus environment and academic experience.

## Dataset Information
The dataset contains various reports and complaints submitted by students. Key attributes include:
- **Report ID:** Unique identifier for each report
- **Date Submitted:** Date the report was submitted
- **Complaint Type:** Category of the complaint (e.g., Academic, Campus Safety, Facilities)
- **Description:** Detailed description of the complaint
- **Severity Level:** Assigned severity level (e.g., Low, Medium, High)
- **Status:** Current status of the complaint (e.g., Open, In Progress, Resolved)

## Project Workflow
1. **Data Loading:** Load the dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** 
   - Analyze the structure and distribution of the data.
   - Check for missing values and handle them appropriately.
3. **Text Preprocessing:** 
   - Tokenize and lemmatize the text data.
   - Generate word clouds to visualize common terms.
   - Categorize age groups based on age data.
4. **Feature Extraction:** Extract meaningful features from the text data using TF-IDF and word embeddings.
5. **Model Development:** Build machine learning models (e.g., SVM, Random Forest) and deep learning models (e.g., LSTM, BERT) to classify and prioritize complaints.
6. **Evaluation:** Evaluate the model's performance using appropriate metrics.
7. **Deployment:** Develop a system to automate the prioritization of new complaints.




