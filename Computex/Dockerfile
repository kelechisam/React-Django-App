FROM ubuntu

RUN apt-get update
RUN apt install python3-pip -y
RUN pip3 install Flask

WORKDIR /app

COPY . .

CMD ["python3", "-m" , "--host=0.0.0.0"]
