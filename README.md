 # ResumeFit: AI-Powered Resume Evaluation Tool

ResumeFit is a cutting-edge tool designed to bridge the gap between job seekers and their dream jobs. Leveraging the power of AI through Google's Generative AI models, ResumeFit evaluates resumes against job descriptions, providing insightful feedback, compatibility scores, and actionable advice to improve candidacy for specific roles. This Streamlit-based web application is intuitive, user-friendly, and crafted to assist both individuals and HR professionals in making informed decisions.

## Features

- **Resume to Job Description Matching**: Dynamically compares the content of a resume with a job description to determine fit.
- **Insightful Feedback**: Offers professional evaluations highlighting strengths, weaknesses, and areas of improvement.
- **Compatibility Score**: Calculates a percentage match to gauge how well the resume aligns with job expectations.
- **Easy to Use Interface**: Built with Streamlit, ensuring a smooth and engaging user experience.

## Getting Started

### Prerequisites

- Python installed on your machine.
- A Google API key for using Google's Generative AI models. Please store this key securely in your environment variables.

### Installation

Follow these steps to get ResumeFit up and running on your local machine:

1. **Clone the Repository**

    Clone the project to your local environment:

    ```bash
    git clone https://github.com/yourgithubusername/ResumeFit.git
    cd ResumeFit
    ```

2. **Install Dependencies**

    Install the necessary Python packages using:

    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Environment Variables**

    Create a `.env` file in the project root and add your Google API key:

    ```plaintext
    GOOGLE_API_KEY=your_api_key_here
    ```

## Running the Application

To launch ResumeFit, execute the following command in your terminal:

```bash
streamlit run app.py
```
# Usage
Start Page: Enter the job description and upload your resume in PDF format.

Evaluation: Click on the "Tell Me About the Resume" or "Percentage Match" button to receive feedback.

Review Feedback: Read through the AI-generated insights to understand how your resume compares to the job description.

# Acknowledgments
Google's Generative AI for the powerful models that drive the core functionality of this tool.

Streamlit for making the development of interactive web applications straightforward and enjoyable.

