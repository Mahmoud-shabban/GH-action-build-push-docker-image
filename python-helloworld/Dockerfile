FROM python:3.8
LABEL maintainer='MAHMOUD'

COPY . /python/app
WORKDIR /python/app
RUN python -m pip install -r requirements.txt

CMD [ "python3" ,"app.py" ]
