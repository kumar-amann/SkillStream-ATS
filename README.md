# SkillStream ATS📜🔔
SkillStream ATS your job synchronizer.
# Live Link : 
https://aman-skillstream-ats.streamlit.app/

SkillStream ATS is an Application Tracking System (ATS) implemented using Streamlit and Google's GenerativeAI API. This tool assists in evaluating resumes based on a given job description, considering the competitive job market. It provides a percentage match with the job description and identifies missing keywords with high accuracy. The generated response includes a structured output containing JD Match percentage, missing keywords, and a profile summary.

Prerequisites
Before running the application, ensure you have the following:

Python installed on your machine.

Necessary Python packages, which can be installed using the following command:

bash
Copy code
pip install streamlit google-generativeai PyPDF2 python-dotenv
Set up your environment variables. Create a .env file in the root directory with the following content:

env
Copy code
GOOGLE_API_KEY=your_google_api_key
Replace your_google_api_key with your actual Google API key.

How to Run
Clone this repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/your-repo.git
Navigate to the project directory.

bash
Copy code
cd your-repo
Run the Streamlit app.

bash
Copy code
streamlit run your_app.py
Open your browser and go to http://localhost:8501 to access the SkillStream ATS application.

Usage
Enter the job description in the provided text area.
Upload a resume in PDF format using the file uploader.
Click the "Submit" button to evaluate the resume.
View the response, which includes the JD match percentage, missing keywords, and a profile summary.
Contributing
If you'd like to contribute to SkillStream ATS, follow these steps:

Fork the repository.
Create a new branch for your changes.
Make your changes and commit them.
Push to your fork and submit a pull request.
License
This project is licensed under the [License Name] - see the LICENSE.md file for details.


