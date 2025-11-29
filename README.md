# NLP - Resume Classifier
Resume Classifier is a Streamlit-powered machine learning application designed to analyze, clean, and categorize resumes into predefined classes. It focuses on understanding and classifying them based on extracted text features.

The tool automatically:
- Extracts text from PDF and DOCX resumes
- Cleans and normalizes noisy text
- Converts resumes into machine-readable form
- Classifies the resume into a category (e.g., Data Science, Developer, Testing, Management, etc.)
- Provides a simple web UI for easy file upload and instant prediction

🔧 Tech Stack

| Component	 | Technology |
| :------- | :------: |
| Web UI	 | Streamlit |
| Text Extraction	| PyPDF2, python-docx |
| Cleaning	| Python Regex| 
| Language	| Python 3.9+ |


# 🛠️ Installation & Setup
1. Clone the repository
~~~
git clone https://github.com/<your-username>/<your-repo>.git
cd resume_builder
~~~

2. Create a virtual environment
~~~
python3 -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
~~~

3. Install dependencies
~~~
pip install -r requirements.txt
~~~

4. Run the Streamlit app
~~~
streamlit run app.py
~~~


Your browser will automatically open at:
~~~
http://localhost:8501
~~~

# 📜 License

MIT License – free to use, modify, and distribute.


🤝 Contributing

Pull requests are welcome!
If you’d like to propose new features, feel free to open an issue.
