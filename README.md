## AI_Resume-Analyzer
By [<b>shamshad ahmed</b>](https://iamsmakhan.netlify.app)

Connect with me on social media and explore my work:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/iamsamkhan/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/iamsamkhan)
[![Medium](https://img.shields.io/badge/Medium-Follow-03a57a?style=flat-square&logo=medium)](https://medium.com/@iamsamkhan)
[![Twitter](https://img.shields.io/twitter/follow/iamsamkhan__?style=social)](https://twitter.com/iamsamkhan__)
[![Shamshad ahmed](https://img.shields.io/badge/Sponsor-sam_khan-28a745?style=flat-square&logo=github-sponsors)](https://github.com/sponsors/iamsamkhan)

**Special Thanks to GitHub Sponsors**


## About The Project:-

The Smart Applicant Tracking System (ATS) is a cutting-edge tool designed to enhance the resume evaluation process. Leveraging advanced Generative AI models from Google, the system empowers users to submit their resumes for a comprehensive analysis based on a provided job description. The system, equipped with a keen understanding of the tech industry, including software engineering, data science, and big data engineering, evaluates resumes in the highly competitive job market. Users can upload their resumes in PDF format, and the system extracts relevant information using PyPDF2. The generated response includes a percentage match with the job description, a list of missing keywords, and a refined profile summary. This innovative solution aims to assist individuals in improving their resumes for optimal performance in the competitive job landscape. The Streamlit web application provides a user-friendly interface, making the resume enhancement process efficient and accessible.

View Live Demo of this project: [Click Here](https://airesume-analyzer-famgnfjlsazqseyndevybd.streamlit.app/)

## Installation Steps

### Option 1: Installation from GitHub

Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the GitHub repository:
     ```
     git clone https://github.com/iamsamkhan/AI_Resume-Analyzer.git
     ```

2. **Create a Virtual Environment** (Optional but recommended)
   - It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
     ```
     conda/venv create -p <Environment_Name> python==<python version> -y
     ```

3. **Activate the Virtual Environment** (Optional)
   - Activate the virtual environment based on your operating system:
       ```
       conda activate <Environment_Name>/
       ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

5. **Run the Project**
   - Start the project by running the appropriate command.
     ```
     python app.py
     ```

6. **Access the Project**
   - Open a web browser or the appropriate client to access the project.


## API Key Setup

To use this project, you need an API key from Google Gemini Large Language Model. Follow these steps to obtain and set up your API key:

1. **Get API Key:**
   - Visit the Provided Link [Click Here](https://makersuite.google.com/app/apikey).
   - Follow the instructions to create an account and obtain your API key.

2. **Set Up API Key:**
   - Create a file named `.env` in the project root.
   - Add your API key to the `.env` file:
     ```dotenv
     GOOGLE_API_KEY=your_api_key_here
     ```

   **Note:** Keep your API key confidential. Do not share it publicly or expose it in your code.<br>
## Project Overview

 Job Application process is no doubt daunting process and resume is the document which represents ourselves to the HR's. When ever we apply for a job and we get a reject without any feedback feels sad right. So i took this as a motivation to my project I created an application using Google generative AI [GEMINI] and built an application where you can get your feedback, and what are the keywords that are missing in your Resume.

## Objectives

- To provide an intuitive tool for job seekers to match their resumes with job descriptions.
- To leverage advanced AI technology for analyzing and providing feedback on resumes.
- To offer a user-friendly interface that simplifies the resume review process.

## Features

- **Resume Upload:** Users can upload their resume in PDF format.
- **Job Description Input:** A text input field allows users to paste the job description they are targeting.
- **AI-Powered Analysis:** Utilizing Gemini AI, the application provides a detailed analysis of the resume in context with the job description.
- **Feedback on Different Aspects:**
  - **Resume Review:** General feedback on the resume.
  - **Skills Improvement:** Suggestions for skills enhancement.
  - **Keywords Analysis:** Identification of missing keywords in the resume.
  - **Match Percentage:** A percentage score indicating how well the resume matches the job description.

## Technologies Used

- **Streamlit:** For creating the web application interface.
- **Google Generative AI (Gemini Pro Vision):** For processing and analyzing the resume content.
- **Python:** The primary programming language used for backend development.
- **PDF2Image & PIL:** For handling PDF file conversions and image processing.

## Challenges Faced

- **Integration with Gemini AI:** Ensuring seamless communication between the Streamlit interface and Gemini AI model.
- **PDF Handling:** Efficiently converting PDF content to a format suitable for analysis by the AI model.
- **User Experience Optimization:** Creating an intuitive and responsive UI.

## Future Enhancements

- **Support for Multiple Pages:** Extend the functionality to handle multi-page resumes.
- **Customizable Feedback Categories:** Allow users to choose specific areas for feedback.
- **Interactive Resume Editing:** Integrate a feature to edit the resume directly based on the AI's suggestions.
- **Enhanced Error Handling:** Improve the system's robustness in handling various file formats and user inputs.

## Conclusion

The **Resume Expert** Streamlit application stands as a significant tool in bridging the gap between job seekers and their ideal job roles. By harnessing the power of AI, it provides valuable insights and recommendations, making it a pivotal step in enhancing the job application process.

---

*Created by sam khan*
