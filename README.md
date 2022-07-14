# chatbot

This is using the turial from the following link: https://pytorch.org/tutorials/beginner/chatbot_tutorial.html 

*try_chatbot_V7* is basically the same, the only difference is that I created 2 double directional GRUs on the hidden layers of another GRU in the encoder.

*try_chatbotV7_conversation_ex1.png* contains an example of a conversation with this chatbot trained for 4 hours on the data in the folder *data*.

*pred_try_chatbot.ipynb* is a code for writing to the chatbot. It loads already trained models by the code *try_chatbot_V* from the folder *save_models* and it loads the movies data so that the bot can build it's vocabulary.  

Please make sure to change all the paths in the code *try_chatbot_V7* to the ones particular to your PC (or google colab or whatever you are using). 
