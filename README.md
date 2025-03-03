# AI Scrapper
- A simple AI web scraper using Ollama, LangChain, and Streamlit by building a RAG(Retrieval-Augmented Generation) system to chat with websites and answer complex questions about the content.


Pre-requisites
Install Ollama on your local machine from the official website. 

And then pull the llama model:

ollama pull llama3.2

Install the dependencies using pip:

pip install -r requirements.txt


Run the Streamlit app:

streamlit run ai_scraper.py



Steps

I am using Mac Pro. Already created VS Code and put 

![image](https://github.com/user-attachments/assets/a1bdfbdb-5b50-4ce0-b720-a92c375aa897)

![image](https://github.com/user-attachments/assets/23f49fac-9de9-4e29-add0-492e8942333a)

I already installed Ollama and ran brew install ollama/tap/ollama  to install Ollama

Follow below steps next to install following supporting components including
streamlit
langchain_core
langchain_community
langchain_ollama
selenium
unstructured


pip install -r requirements.txt

![image](https://github.com/user-attachments/assets/75693403-5eb9-4d14-8b19-243e6097de4e)


Next execute from prompt 
streamlit run ai_scraper.py   --> it will open AI Scraper page in new browser window
](http://localhost:8501/  
![image](https://github.com/user-attachments/assets/16072fa6-0326-4f52-8818-2c2909fdd484)


Then you can open the web page to scrap the content like below

I opened one rediff page with following content
![image](https://github.com/user-attachments/assets/ccaad5ea-082f-40bb-88f3-81526280137a)


![image](https://github.com/user-attachments/assets/a4e80ca8-1a7c-4c55-ab7a-5882f8b1a024)


I searched for below pattern and AI Scrapper pulled below details from web site

![image](https://github.com/user-attachments/assets/184e7129-d93b-4103-a48f-f1755f964307)

![image](https://github.com/user-attachments/assets/ffb62e34-ca2f-4269-84ac-90f7aa6e2785)


This is a very basic example, but we can enhance to get more specific data by enhancing the code


