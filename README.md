# AJDMS
AJDMS – Judicial Decision-Making System: LLM-Based Judge with Multi-Agent Jury for Automated Legal Adjudication in the Indian Judicial Framework.  AJDMS is a legal decision-support engine designed to simulate judicial reasoning and case verdict delivery in the Indian context.

Features
Upload or input case arguments in natural language format.

AI Judge delivers judgments based on Indian case law references.

AI Jury agents deliberate independently, discuss, and vote on verdicts.

Structured legal reasoning and justification based on precedents.

Real-time decision explanation using XAI modules.

Secure processing with on-premises deployment support.

Interactive UI powered by Streamlit.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/ajdms-judge-system.git
Navigate to the project directory:

bash
Copy
Edit
cd ajdms-judge-system
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Create a .env file in the root folder and add your Google API key:

env
Copy
Edit
GOOGLE_API_KEY=your_google_api_key
Usage
Run the Streamlit application:

bash
Copy
Edit
streamlit run app.py
The application will open in your default browser. You can then:

Enter the case arguments or legal scenario in plain English.

Let the system process the inputs using LLM-based Judge and AI Jury agents.

View a structured legal verdict with cited references.

Verdicts will include the Judge’s explanation and the Jury’s voting consensus.

Libraries Used

Library	Purpose
streamlit	For building the interactive web app UI
google-generativeai	Accessing Gemini model for text understanding
python-dotenv	For secure storage of API keys
pydub	Audio processing (optional use-case for speech input)
numpy	Numerical operations during jury voting simulations
streamlit-webrtc	For adding real-time audio/video interaction features (optional)
Deployment
Local Deployment
Follow the instructions above under the Usage section.

Cloud Deployment
This application can be deployed to platforms like:

Streamlit Sharing
You can directly deploy on Streamlit Cloud by linking your GitHub repository.

Cloud Services (AWS, GCP, Azure)
You can also deploy the app to AWS EC2, Google Cloud Run, or Azure App Services by containerizing or hosting the Python environment.

Contributing
Feel free to contribute! Read the guidelines here:
📌 Contribution Guide

License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this for academic and research purposes.
