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

Example 4
- Merge Example 2 and Example 3 into a new working example
- Run Rasa in a container. Make the other containers dependent on the rasa container chatbot.
- Move the chatbot pop up UI into the Flask data able main page.
- Rasa docker info https://rasa.com/docs/rasa/docker/building-in-docker
 - investigate this approach https://rasa.com/blog/custom-rasa-nlu-docker-container/


 Other notes:

 Delete all docker images: docker rmi -f $(docker images -a -q)

