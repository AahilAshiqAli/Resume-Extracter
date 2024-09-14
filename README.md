# Resume-Matching-with-JD
6th semester Information Retrieval project developed in python getting top resumes that match given job description by extracting features from resume and Job description using NER model and applying VSM to calculate scores.
To run this project, you would need to make a folder named job desc in which you will put your job description file and then you will have to make a folder named cvs txt in which you will have to add cvs files
To run this code, get into Project directory and run this all commands
First install all these libraries
pip install streamlit
pip install spacy
python -m spacy download en_core_web_sm
pip install nltk
pip install numpy
pip install scipy
pip install pandas

Then to run streamlit project
streamlit run Project.py
