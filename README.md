# ChatPDF

This is a PDF summarizer website using LangChain framework. 
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
