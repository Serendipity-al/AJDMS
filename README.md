# AJDMS: Judicial Decision-Making System
 LLM-Based Judge with Multi-Agent Jury for Automated Legal Adjudication in the Indian Judicial Framework.

 AJDMS is a legal decision-making engine designed to assist in automating judicial reasoning and verdict delivery within the 
 Indian judicial system. It aims to address the massive case backlog and inconsistencies in legal rulings by simulating the 
 judgment process digitally.

 # Features
- Digital Judge – Analyzes legal arguments and delivers verdicts based on Indian case law.

- AI Jury – Multiple agents debate and vote to simulate real jury decisions.

- Legal Database Integration – Pulls real judgments from Indian Kanoon for accurate referencing.

- Explainable Verdicts – Provides clear reasoning and case citations for every decision.

- Voice Input Support – Allows users to submit cases using speech.

- Secure Deployment – Keeps legal data safe with on-premise setup and encryption.


  ## Installation

  1.Clone the repository

  git clone https://github.com/yourusername/AJDMS.git
  cd AJDMS

  2.Create a virtual environment (optional but recommended)

  python -m venv venv

  For Windows:

  venv\Scripts\activate


  3.Install dependencies

  pip install -r requirements.txt

  4.Set up environment variables

  Create a .env file in the root folder and add your key:

  GOOGLE_API_KEY=your_google_generative_ai_key

  5.Run the application:

  streamlit run app.py

  ## Usage
  1.start the Application

  streamlit run app.py

  2.Enter or speak the details of a legal case in the interface.
  3.The system analyzes the input, retrieves relevant Indian case law, and provides a verdict.
  4.The AI Jury deliberates and votes on the outcome.
  5.Final result includes the verdict with a clear explanation and case references.

  




  
    
  


  



  










