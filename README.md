# SalesRep-AI-Sales-Bot
This is a Demo Project on seeing how a power of LLM's could be utilized to add AI to a Sales Bot

![promo1](https://github.com/Hamas-ur-Rehman/Sales_AI_BOT/assets/47780362/242d2aaa-c287-48f6-8d8f-0cd2fa44d27d)
![promo2](https://github.com/Hamas-ur-Rehman/Sales_AI_BOT/assets/47780362/0a324ac6-836d-4d0b-8307-b09835d7b2ae)

## Miscellaneous 
- The prompts can be found inside of the prompts.py file

## Installation Instructions (*work in progress*)
- For mac have xcode installed
- Open Terminal and run the following step by step
```console 
xcode-select --install
```
- Users running macOS High Sierra, Sierra, El Capitan, or earlier, run: 
```console 
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
- Users running Catalina, Mojave, or Big Sur, run: 
```console 
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
- Enter your administrator password when prompted and press Return to continue. Wait for the download to finish
- Remember to restart
- Now run this 
```console 
python3
``` 
if you get no errors you can skip the next step else do it
- https://www.scaler.com/topics/python/how-to-install-python-on-macos/ open this guide and follow to install python
- now create a folder where we will store all these files you can open a terminal inside that folder cd into it
- now inside the terminal make sure you are in the folder run the following commands
```console
pip install virtualenv
```
```console
virtualenv env
```
```console
source env/bin/activate 
```
```console
pip install langchain openai unstructured unstructured[local-inference] chroma chromadb python-dotenv tiktoken gradio langdetect deep-translator llama-index
```
```console
git clone https://github.com/Hamas-ur-Rehman/SalesRep-AI-Sales-Bot
```
```console
cd SalesRep-AI-Sales-Bot
```
```console
python3 main.py
```
- Now please be paitent while it loads and after that you can try talking to it
- **IMPORTANT** remember to add your openAI API key into the main.py file on line 3
- Create a file called .env and add the following line to it make sure this file is in the same folder as the main.py file
```console
OPENAI_API_KEY= ADD YOU OPEN AI API KEY HERE
```

## TODOS: IMPORTANT + URGENT
- [x] Create an Inteface for the Demo
- [x] Work on Seperating the prompts to a seperate File for easier prompt injection
- [x] work on the installation instructions
- [ ] if user engages in Swedish language, so will Alice. 
- [x] make sure to qualify user preferences before recommending a product. at least 2 to 5 qustions before any product recommendation. 
- [ ] make text from Alice always short, not longer than 10 words in the beginning of the conversation
- [x] add introduction line with "Hey, can I help you get something?"

## TODOS: IMPORTANT + NOT URGENT
- [ ] Add prefilled conversation suggestions that will make it easier for the user to keep the conversation going
- [ ] make the chat response time faster
