#FROM python:3
FROM pytorch/pytorch
RUN apt-get update
COPY . .
RUN pip install -r requirements.txt
RUN python loadnltk.py
CMD python chat.py
