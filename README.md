# Pika-Food_Ordering_Chatbot (END-END NLP PROJECT)
FastAPI-powered food-ordering chatbot using Dialogflow and Mysql. Effortlessly place, modify, and track orders for an enhanced dining experience.

Screenshots:

<img width="889" alt="01" src="https://github.com/VarsaGupta/Pika-Food_Ordering_Chatbot/assets/125072517/9acc6766-70fb-49d8-8867-52fe378eda91">
<img width="877" alt="02" src="https://github.com/VarsaGupta/Pika-Food_Ordering_Chatbot/assets/125072517/41e01e8d-b9ba-437c-8561-143cf3e1db66">
<img width="323" alt="03" src="https://github.com/VarsaGupta/Pika-Food_Ordering_Chatbot/assets/125072517/865ddd0e-e705-4d40-9ba7-7d8447cc45de">
<img width="354" alt="04" src="https://github.com/VarsaGupta/Pika-Food_Ordering_Chatbot/assets/125072517/1ebd0dd7-78ac-49a3-9541-dde25a69648c">
<img width="300" alt="05" src="https://github.com/VarsaGupta/Pika-Food_Ordering_Chatbot/assets/125072517/323fb729-18c6-4b91-8b9c-0446a7188f99">



Directory structure
===================
backend: Contains Python FastAPI backend code
db: contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
dialogflow_assets: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================
pip install mysql-connector
pip install "fastapi[all]"
OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.   

