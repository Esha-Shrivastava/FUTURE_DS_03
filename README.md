🎓 Task 3 – College Event Feedback Analysis 

**Internship:** Future Interns – Data Science & Analytics  
**Track Code:** DS  
**Intern:** Esha Adhya Shrivastava  
**CIN ID:** FIT/JUN25/DS2805  
**Task Number:** FUTURE_DS_03

📌 Objective

To analyze student feedback data from campus events and convert raw responses into actionable insights using Python and basic NLP tools. The goal was to help event organizers understand satisfaction levels and areas of improvement.

📁 Dataset

- **Source:** Kaggle – [Student Feedback Survey Responses](https://www.kaggle.com/datasets/ruchi798/student-feedback-survey-responses)
- **File Used:** `student_feedback.csv`

🛠 Tools & Libraries Used

1. Google Colab – For running Python-based Jupyter notebooks without local setup

2. pandas – Used for data manipulation, exploration, and cleaning

3. seaborn & matplotlib – For creating clear and insightful visualizations

4. TextBlob – Applied for performing sentiment analysis using basic NLP techniques

📊 Key Tasks Performed

Step 1: Data Cleaning and Preparation
- Removed unnecessary columns
- Renamed columns for clarity

Step 2: Ratings Overview
- Calculated average feedback scores
- Created:
  - 📊 Bar chart of average ratings
  - 🔥 Heatmap showing correlation between feedback categories
  - 🥧 Pie chart of course recommendation distribution

Step 3: Sentiment Analysis
- Simulated realistic student comment data
- Applied TextBlob to extract sentiment polarity
- Categorized comments as Positive, Neutral, or Negative
- Visualized sentiment distribution

Step 4: Final Recommendations

💡 Key Insights

- Subject knowledge and concept clarity received the highest ratings, indicating students were confident in the instructors’ expertise    and delivery.
- Assignment difficulty and doubt resolution scored lower, suggesting students faced challenges with workload and real-time support.
- Sentiment analysis revealed a **predominantly positive tone** in comments, with some areas needing attention.

> Recommendations for Organizers

1. Balance the difficulty level of assignments to avoid overwhelming students while maintaining quality.

2. Improve doubt-solving mechanisms (e.g., doubt-clearing sessions, discussion forums).

3. Keep strengthening subject delivery and concept clarity, as they are key student strengths.

4. Periodic feedback loops can help identify and act on evolving concerns.

📎 Files Included

- `College_Event_Feedback_Analysis.ipynb` – Google Colab notebook with full analysis
- `student_feedback.csv` – Original dataset used



