# CHAT-BOT
Introduction
In this project I have presented a chatbot that generates a dynamic response for online client's queries. The Proposed System is based on Artificial Intelligence-powered Chatbot. The web based platform provides a vast intelligent base that can help simulate problem- solving for humans. This proposed chatbot identifies the user context which triggers the particular intent for a response. Since it is responding dynamic response, the desired answer will be generated for the user. The proposed system used machine learning algorithms to learn the Chatbot by experiencing various user's responses and requests. Chat-bot is that it comes to use in numerous fields of our daily life. Nowadays chat-bot is started to becoming so robust because Artificial Intelligence aids the human touch in every conversation, chat-bot understand the user's query, and trigger an accurate response.

Methodology
How do the Chatbots function? The main technology that lies behind chatbots is NLP and Machine Learning. When a question is presented to a chatbot, a series or complex algorithms process the received input, understand what the user is asking, and based on that, determines the answer suitable to the question.
![image](https://github.com/shristy-chaudhary/CHAT-BOT/assets/110960844/e362bcfe-e325-430f-b3c0-d516e67ffc57)
Chatterbot is a library in python which generates a response to user input. It used a number of machine learning algorithms to generates a variety of responses. It makes it easier for the user to make a chatbot using the chatterbot library for more accurate responses. The design of the chatbot is such that it allows the bot to interact in many languages which include Spanish, German, English, and a lot of regional languages. The Machine Learning Algorithms also make it easier for the bot to improve on its own with the user input.

We’ll take a step-by-step approach and eventually make our own chatbot.
![image](https://github.com/shristy-chaudhary/CHAT-BOT/assets/110960844/e858206c-6f80-48b0-bdc7-7f3673df7f78)

Step 1. Install the Chatterbot and chatterbot corpus module :

The first and foremost step is to install the chatterbot library. You also need to install the chatterbot corpus library. Basically, Corpus means a bunch of words. The Chatterbot corpus contains a bunch of data that is included in the chatterbot module. The corpus is used by bots to train themselves.

Step 2. Import the modules

we have to import two classes: Chatbot from chatterbot and List Trainer from chatterbot. Trainers. List Trainer: Allows a chatbot to be trained using a list of strings where the list represents a conversation.

Step 3. Name our Chatbot:

Now, we will give any name to the chatbot of our choice. Just create a Chatbot object. Here the chatbot is maned as “Bot” just to make it understandable.

Step 4. Use of Logic Adapter:

The Logical Adapter regulates the logic behind the chatterbot that is, it picks responses for any input provided to it. This parameter contains a list of all the logical operators. When more than one logical adapter is put to use, the chatbot will calculate the confidence level, and the response with the highest calculated confidence will be returned as output.

Here we have used two logical adapters:

BestMatch: The BestMatchAdapter helps it to choose the best match from the list of responses already provided. TimeLogicAdapter: The TimeLogicAdapter identifies statements in which a question about the current time is asked. If a matching question is detected, then a response containing the current time is returned. ** Step 5. Training, Communication, and Testing :**

For the training process, you will need to pass in a list of statements where the order of each statement is based on its placement in a given conversation. We have to train the bot to improve its performance for this we need to call the train() method by passing a list of sentences. Training ensures that the bot has enough knowledge to get started with specific responses to specific inputs. After training, let’s check its communication skills. And the last step is to do testing

