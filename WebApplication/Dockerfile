FROM python:3

WORKDIR /usr/src/app

RUN mkdir upload

RUN pip install --no-cache-dir tornado

COPY ./index.html .

COPY ./index.py .

EXPOSE 8080

CMD [ "python", "./index.py" ]