FROM python:3.9-alpine

WORKDIR /flask

COPY requirements.txt .

RUN pip3 install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 8000

CMD [start.sh]
