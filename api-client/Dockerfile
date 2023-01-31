FROM python:3-alpine
#RUN pip3 install sockets
COPY . /app
WORKDIR /app
EXPOSE 5000
ENTRYPOINT ["python3", "socket_client.py"]
