# ChatPDF

This is a PDF summarizer website using LangChain framework. The idea behind this website is to help students get the summary of PDFs of study material to help them study easier. The future idea is to expand this to a website where students upload their PDF and are asked questions based on the summary generated to aid their revision along with periodic revision by sending notifications or emails, where each student has their own account and their own study material. 

To access the website, run the following commands:

# First run this command
pip install streamlit openai langchain pypdf2

# Use your own OpenAI API Key in the code 

# If you are running on Colab use the following command to access the website
!npm install localtunnel
!streamlit run app.py &>/content/logs.txt & npx localtunnel --port 8501 & curl ipv4.icanhazip.com
Use the endpoint IP generated in the output in the generated website to access ChatPDF 

# To run on local terminals, use the following command
streamlit run app.py
