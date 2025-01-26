# Evaluation of AI-Powered Chatbots and Voice Assistants in User Experience
# Overview
This project evaluates user experiences with AI-powered chatbots and voice assistants, focusing on key metrics such as usability, task efficiency, emotional engagement, and overall satisfaction. Using a structured dataset collected via Google Forms, the study employs both quantitative and qualitative analyses, including the AttrakDiff model, to assess hedonic (emotional) and pragmatic (functional) qualities. The findings provide actionable insights for improving user interactions with AI systems.

# Dataset
The dataset consists of 530 user responses collected via a questionnaire designed to evaluate various aspects of user experience. It is divided into four sections:

Demographic Information: Age, gender, education level, and familiarity with AI chatbots.
Pragmatic Attributes: Usability, task performance, and reliability.
Hedonic Attributes: Emotional engagement, enjoyment, and interaction quality.
General Evaluation and Suggestions: User likes, dislikes, and recommendations for improvement.
Dataset Highlights
Size: 530 responses
Format: CSV
Attributes: Quantitative ratings and qualitative feedback
# Objective
The primary goals of this project include:
Assessing user satisfaction, emotional engagement, and task completion.
Measuring hedonic and pragmatic qualities using the AttrakDiff model.
Identifying user likes, dislikes, and suggestions to improve AI chatbot design.
# Project Workflow
1. Data Collection
Questionnaire created using Google Forms.
Responses exported in CSV format for analysis.
2. Data Preprocessing
Handled missing values and cleaned text responses.
Standardized ratings and normalized open-ended feedback.
Converted qualitative feedback into themes using word clouds.
3. Quantitative and Qualitative Analysis
Descriptive Statistics: Mean, sentiment analysis, and distribution of ratings for usability, satisfaction, and task efficiency.
AttrakDiff Model: Weighted averages calculated for hedonic (3.67) and pragmatic (3.22) qualities, visualized through radar and bar charts.
Qualitative Themes: Summarized user likes, dislikes, and improvement suggestions using word clouds.
#  Results
Quantitative Metrics
Ease of Use: Average rating of 4.2/5.
Task Completion: 85% success rate.
Overall Satisfaction: 4.1/5 on average.
AttrakDiff Model Results
Pragmatic Quality: 3.22 (moderate usability and task efficiency).
Hedonic Quality: 3.67 (strong emotional engagement).
Key Insights
Users appreciated ChatGPT’s ease of use, speed, and engaging interactions.
Common complaints included inaccuracies, slow responses, and limited contextual understanding.
Suggestions included improving accuracy, response times, and support for multimedia input.
# Visualizations
Included Visuals:
Bar Charts: Distribution of ratings for key attributes (e.g., ease of use, engagement).
Radar Plot: Comparison of hedonic and pragmatic quality scores.
Word Clouds: Highlighting user likes, dislikes, and suggestions.
# Dependencies
To run this project, you’ll need the following Python libraries:

pandas
numpy
matplotlib
seaborn
wordcloud
scikit-learn
How to Run the Project
Clone the repository:
bash
Copy
Edit
git clone https://github.com/PsalmTech/Evaluation_of_AI-Chatbots.git
Navigate to the project directory:
bash
Copy
Edit
cd Evaluation_AI_Chatbots
Upload the dataset (User Experience Feedback.csv) to the project folder.
Open and execute the Jupyter Notebook (Evaluation_AI_Chatbots.ipynb) in Visual Studio Code or JupyterLab.
# Future Work
Feature Expansion: Include user feedback on multimedia input and accessibility.
Comparative Analysis: Benchmark against other AI chatbots like Google Bard or Alexa.
Advanced Modeling: Explore sentiment prediction models and conversational flow analytics.

License
This project is released under the CC0: Public Domain License.

# Acknowledgements
Special thanks to:
The participants who contributed their valuable feedback.
Developers of the Python libraries used in this project.

# Developer:
Samuel Abiodun Ojeleke M.Sc. Computer Science Candidate, Federal University Oye Ekiti. Email: ojelekesamuel4@gmail.com Linkedin: https://www.linkedin.com/in/samuel-ojeleke
