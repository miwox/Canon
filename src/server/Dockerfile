#Dockerfle for the mongoqueries container
FROM python:latest
WORKDIR /server
ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY  server.py server.py
CMD ["python", "./server.py"]