# **Smart ATS – AI-Powered Resume Analyzer** 🚀  

**🔗 Live Demo:** [Click here to try it on Streamlit](<[your_streamlit_deployment_link](https://sai1721-ats-using-llm-ats-odcyzs.streamlit.app/)>)  

## **📌 About**  
**Smart ATS (Application Tracking System)** is an AI-powered resume evaluator that helps job seekers optimize their resumes based on job descriptions. This tool utilizes **Google Gemini AI** to analyze resumes, match them with job descriptions, and provide insights on missing keywords and profile relevance.  

## **✨ Features**  
✅ Upload your **PDF resume** for analysis  
✅ Get a **match percentage** with the job description  
✅ Identify **missing keywords** for better ATS optimization  
✅ Generate a **profile summary** based on the resume  
✅ Built using **Streamlit + Google Gemini AI**  

## **⚙️ How It Works**  
1. **Paste the Job Description** in the text area.  
2. **Upload your Resume** (PDF format).  
3. Click **Submit**, and the AI will analyze your resume.  
4. View the **match percentage, missing keywords, and profile summary**.  

## **🛠️ Tech Stack**  
- **Python**  
- **Streamlit** (Web UI)  
- **Google Gemini AI** (LLM for text analysis)  
- **PyPDF2** (PDF processing)  

## **🚀 Installation & Running Locally**  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/Sai1721/ATS_using_LLM.git
   cd ATS_using_LLM
2. **Create a virtual environment**(optional but recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate     # Windows
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
4. **Set up API Key**
   Locally: Create a .env file and add your Google API key (DO NOT commit this file).
   ```bash
   GOOGLE_API_KEY=your_gemini_api_key_here
5. **Run the application**
   ```bash
   streamlit run app.py
