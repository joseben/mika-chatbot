# mika-chatbot

### Run using the following lines of command

Run these commands inside the chatbot folder

##### To train the model use
docker run -v `pwd`:/app rasa/rasa:3.5.5-full train 
##### To run the chatbot use
docker run -it -v $(pwd):/app rasa/rasa:3.5.5-full shell
