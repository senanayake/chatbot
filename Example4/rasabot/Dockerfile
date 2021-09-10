FROM rasa/rasa

WORKDIR /app
COPY . ./app
CMD [ "run","-m","/app/models","--enable-api","--cors","*"]
EXPOSE 5005
