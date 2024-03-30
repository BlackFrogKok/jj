FROM python:3.12.1-alpine3.19

WORKDIR /app

COPY . .

RUN pip3 install --upgrade pip

RUN pip3 install -r requirements.txt && rm requirements.txt

RUN export FLASK_ENV=development