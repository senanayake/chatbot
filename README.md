# chatbot
hacking chatbot example code

Example 1 - A dockerized command line chatbot.
Essential a dockerized version of 
https://github.com/python-engineer/pytorch-chatbot

pushed to dockerhub with
docker build -t senanayake76/chatbot:example1
docker push senanayake76/chatbot:example1
docker pull senanayake76/chatbot:example1
docker run -it senanayake76/chatbot:example1

Example 2 
- shows a simple RASA chatbot
- The chatbot is the default example created by "rasa init"
- an index.html page is included that can pop up a chat window and talk to a RASA chatbot running locally on the machine.

Example 3
- Flask dataable example
- A free dashboard starter  https://appseed.us/admin-dashboards/flask-datta-able
- in a subsequent example, explore hacking a dashboard into a product page + the chatbot windown in example 2 into a coherent working example.
- Example can be run using 
-  docker-compose pull &&  docker-compose build &&  docker-compose up -d
- browse to http://localhost:5005/ create an account and login.




