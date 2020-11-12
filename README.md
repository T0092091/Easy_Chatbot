## INSTALLATION:
<br> `pip install -r requirements.txt`
<br><br>
Python EXECUTION: Run `conversation.py` to run the bot<br>



We will be using AIML because to build a chatbot using NLP/ML/Deep Learning takes a lot of time to build while AIML helps to build a chatbot easily but the only problem is that you need to feed as many data as you can for the bot to learn and here data doesn't just mean the questions and its category but also the question pattern.
 

Here you will need 3 files:

1 Python file: conversation.py<br>
2 aiml file: learningFileList.aiml, and conversation.aiml<br>

##### conversation.py
code for loading and running the bot

##### learningFilesList.aiml
code to load the files to train

##### data folder
Data folder contains all the AIML files<br>
Each aiml file contains the conversation patterns which the kernel will load for chatting

Note: Kernel object is the public interface to the AIML interpreter. "learn" method loads the contents of an AIML file into the kernel. While "respond" method is used to get the response from the learned AIML file. And "LEARN AIML" is the pattern that k.respond from conversation.py calls. The <learn> tag loads the AIML file to respond.

#### Demo OUTPUT:
```Loading learning_file_list.aiml…done (0.07 seconds)
Loading conversation.aiml…done (0.00 seconds)
User > Hello Bot
bot > Hello! Nice to meet you.

I also installed another version of AIML as the current AIML is only for python2. But since I have python3 installed, I cloned a python aiml from github https://github.com/weddige/pyaiml3.
