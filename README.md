# Chat-bot
create chat bot using python,ML and NLP


So what is chat bot?

A chat bot is an Artificial intelligence-powered piece of software, application, website or network to perform particular task like to get info about particular task using chatbots.



How chatbots do works?

There are two types of chatbots.They are:
            1. Rule-based approach: In this they answers question based on some rules in which it trained on.These rules defined very simple to very complex.The bots can handle simple queries but fail to manage complex ones.
            2. self learning: These are ones that use some machine learning algorithms based approach and are deinitely more efficient than rule-based approach
                  Again, these are of two types:
                    i. retrivel-based model
                    ii. generative
 
 First we will do pre-processing text which inlcudes:
  we download article using Article module then we tokenize our text so that it will seperate sentences into strings with seperated spaces
  
  
  
  Greeting responses from bot will get randomly with given greetings with respect to different user greetings.In bot response we will use countvectorizer and fit our input sentence and find similarities between our given input and sentence present in article and those similarities will sort as index and set response flag is  equal to 0.If response flag equal to 0 it means it will print "I apolozise, I don't understand", means similarities are not same.it will give response utill we give input as exit_list.
  
  
 Conclusion:
              Though it is a very simple bot with hardly any cognitive skills, it’s a good way to get into NLP and get to know about chatbots.Though ‘ROBO’ responds to user input. It won’t fool your friends, and for a production system you’ll want to consider one of the existing bot platforms or frameworks, but this example should help you think through the design and challenge of creating a chatbot. Internet is flooded with resources and after reading this article I am sure, you will want to create a chatbot of your own. So happy tinkering!!
  


