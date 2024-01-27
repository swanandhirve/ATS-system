ATS System with Google GenAI, PDF2Image, and Streamlit
Overview
This project is an Applicant Tracking System (ATS) that utilizes Google Cloud's Natural Language API for text analysis, PDF2Image for converting PDF resumes to images, and Streamlit for creating a user-friendly web application.

Features
Resume Parsing: Extracts relevant information from resumes using Google Cloud's Natural Language API.
PDF to Image Conversion: Converts PDF resumes to images for easy processing.
User Interface: Provides a user-friendly interface to interact with the ATS system.
Prerequisites
Before running the application, make sure you have the following installed:

Google Cloud SDK
PDF2Image
Streamlit
Additionally, set up a Google Cloud project and enable the Natural Language API.

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/swanandhirve/ATS-system.git
cd ats-system
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Configure Google Cloud credentials:

Set up the necessary environment variables with your Google Cloud credentials.

bash
Copy code
export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/credentials.json"
Usage
Run the Streamlit application:

bash
Copy code
streamlit run app.py
Access the ATS system at http://localhost:8501 in your web browser.

Upload PDF resumes through the user interface.

The system will process the resumes, extract relevant information, and display the results.

Customization
Feel free to customize the application based on your requirements. You can modify the Streamlit app layout, add more features, or integrate additional services.

Troubleshooting
If you encounter any issues, refer to the troubleshooting section in the documentation for solutions.

Acknowledgements
Google Cloud for providing Natural Language API.
PDF2Image for PDF to image conversion.
Streamlit for creating interactive web applications.
License
This project is licensed under the MIT License.

Feel free to adapt and expand upon this template to provide more detailed information about your project. Include additional sections or instructions as needed.


![image](https://github.com/swanandhirve/ATS-system/assets/87373408/5bbe737a-00e4-458c-b0f8-2cf61d18d679)


![image](https://github.com/swanandhirve/ATS-system/assets/87373408/0bd634d1-9526-4a3e-95d0-5338de03472e)


![image](https://github.com/swanandhirve/ATS-system/assets/87373408/c18ac3b1-de5b-47ab-b0da-8acf922a0aba)
