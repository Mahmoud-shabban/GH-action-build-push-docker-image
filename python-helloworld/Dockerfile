FROM python:3.8

LABEL maintainer='MAHMOUD'

WORKDIR /python/app

COPY . /python/app

RUN python -m pip install -r requirements.txt

CMD [ "python3" ,"app.py" ]
