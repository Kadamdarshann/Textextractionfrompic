# Text Extraction from picture
🚀 How to Run the Application Locally
Follow these steps to set up and run the project on your local machine:

✅ Prerequisites
Anaconda/Miniconda

Tesseract OCR (Windows)

Python 3.x

🧭 Steps
1.Clone the Repository

bash
Copy code
git clone <repository_url>
cd <project_folder>
2.Create a Virtual Environment

bash
Copy code
conda create --name ocr_env python=3.9
3.Activate the Environment

bash
Copy code
conda activate ocr_env
4.Install Tesseract OCR
Download and install from here.

5.Locate the Tesseract Path
Default (check yours):

makefile
Copy code
C:\Program Files\Tesseract-OCR\tesseract.exe
6.Update Path in Code
In your Python script:

python
Copy code
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
7.Install Python Dependencies

bash
Copy code
pip install -r requirements.txt
8.Run the Application

bash
Copy code
python app.py
9.Access the App
Open your browser and go to the URL displayed (e.g., http://127.0.0.1:5000/).

10.Test the App
Use sample images from the sample_data/ folder for quick testing.
