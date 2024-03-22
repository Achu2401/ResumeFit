# ResumeFit-AI-Powered-Resume-Evaluation-Tool
ResumeFit is a cutting-edge tool designed to bridge the gap between job seekers and their dream jobs. Leveraging the power of AI through Google's Generative AI models, ResumeFit evaluates resumes against job descriptions, providing insightful feedback, compatibility scores, and actionable advice to improve candidacy for specific roles. This Streamlit-based web application is intuitive, user-friendly, and crafted to assist both individuals and HR professionals in making informed decisions.

Features
Resume to Job Description Matching: Compares the content of a resume with a job description to determine fit.
Insightful Feedback: Offers professional evaluations highlighting strengths, weaknesses, and areas of improvement.
Compatibility Score: Calculates a percentage match to gauge how well the resume aligns with job expectations.
Easy to Use Interface: Built with Streamlit, ensuring a smooth user experience.
Getting Started
Prerequisites
Before running ResumeFit, you'll need to have Python installed on your machine. Additionally, you must obtain a Google API key to use Google's Generative AI models. Store this key securely in your environment variables.

Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourgithubusername/ResumeFit.git
cd ResumeFit
Install the required Python packages:
bash
Copy code
pip install -r requirements.txt
Create a .env file in the root directory and populate it with your Google API key:
plaintext
Copy code
GOOGLE_API_KEY=your_api_key_here
Running the Application
To launch ResumeFit, run the following command in your terminal:

bash
Copy code
streamlit run app.py
Navigate to the URL provided in the terminal to access the web application.

Usage
Start Page: Enter the job description and upload your resume in PDF format.
Evaluation: Click on the "Tell Me About the Resume" or "Percentage Match" button to receive feedback.
Review Feedback: Read through the AI-generated insights to understand how your resume compares to the job description.
Contributing
Contributions are welcome! If you have suggestions for improvements or bug fixes, please feel free to fork the repository, make your changes, and submit a pull request.


Acknowledgments
Thanks to Google's Generative AI for powering the core functionality of this tool.
Appreciation for the Streamlit library, making interactive web applications accessible to all.
