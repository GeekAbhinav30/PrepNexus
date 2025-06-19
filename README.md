# PrepNexus 

PrepNexus is an AI-powered Resume Analysis and Interview Preparation system designed to enhance job search and interview success.

Features
It reads and analyzes resumes using a fine-tuned RoBERTa model to recommend the best job roles suited to user profile.

Interview Chatbot presents a cpomprehensive Q&A as per the job role so as to help candidates prepare. It is built with LangChain and ChromaDB, powered by LLaMA-3 (8B). 

With the help of BeautifulSoup, job listings are fetched from Indeed, improving job search efficiency by 40%.


Colab NoteBook- https://colab.research.google.com/drive/1VaYEu3t2gSwZVSnrphnTtNhuV61_PC8u
of RoBERTa for
resume role predictor.


## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/GeekAbhinav30/PrepNexus.git
   cd PrepNexus
python -m venv env
# Windows
.\env\Scripts\activate

pip install -r requirements.txt

# macOS/Linux
source env/bin/activate

pip install -r requirements.txt
