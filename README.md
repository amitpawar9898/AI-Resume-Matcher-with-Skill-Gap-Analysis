# AI-Resume-Matcher-with-Skill-Gap-Analysis
🧠 AI Resume Analyzer
An AI-powered Resume Analyzer built using Python, Scikit-learn, and Matplotlib that compares your resume with a job description and visually displays your skill match percentage and missing skill gap.

🚀 Features
Uses TF-IDF Vectorization and Cosine Similarity to calculate how well your resume matches the job description.
Generates visual insights using Matplotlib:
Bar chart showing Resume Match Score
Pie chart showing Match vs Missing Skills
Simple command-line interface for text input.
Easy to customize or integrate into a web app.

🧩 Technologies Used
Python 3.x
Scikit-learn (for NLP and similarity computation)
Matplotlib (for data visualization)
Numpy (for numerical operations)

⚙️ Installation
Clone the repository:
git clone https://github.com/yourusername/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
Install dependencies:
pip install numpy scikit-learn matplotlib

💡 How It Works
Input:
Paste your resume text when prompted.
Paste the job description text for comparison.
Processing:
The code vectorizes both inputs using TfidfVectorizer.
It calculates the Cosine Similarity between them to measure textual overlap.
Output:

A match score (percentage) between your resume and job description.

A bar chart and pie chart showing match and missing skills visually.
