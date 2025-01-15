# Emotional-Support-Chatbot

This project aims to build an emotional support chatbot that can understand and analyze users' emotions through text and voice inputs. The chatbot utilizes advanced machine learning models for sentiment analysis and emotion detection and provides personalized, multilingual responses. The chatbot can support users in a variety of emotional states and offer referrals for professional help if necessary.



# How to run it?

First step is to download the models from the link <a href="https://drive.google.com/drive/folders/1Xy7M-HgV8XbDfTztSnUUfiM1PriykRMS?usp=drive_link"> MODEL </a> add the model in the root project directory.

The following instructions were tested on the Windows and Linux with Python 3.8.

1. Clone this repository

```
git clone https://github.com/dhriti-exe/Emotional-Support-Chatbot.git
```
```
cd Mental-health-Chatbot/
```

2. Create and activate virtual environment 

```
python -m venv venv
```
on Linux system
```
source venv/bin/activate
```
on Windows system
```
.\venv\Scripts\activate.bat
```
3. Install requirements

```
pip install  -r requirements.txt
```

4. Run the 
```
flask --app app --debug run
