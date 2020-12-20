FROM alpine:3.9

LABEL maintenare = "Mordechai Ochayon"

RUN apk update

RUN apk add python3

RUN pip3 install click==7.0

RUN pip3 install Flask==1.0.2

RUN pip3 install itsdangerous==1.1.0

RUN pip3 install Jinja2==2.10

RUN pip3 install MarkupSafe==1.1.1

RUN pip3 install Werkzeug==0.14.1

COPY . /src

WORKDIR /src

EXPOSE 5000

CMD  ["python3", "./app.py"]
