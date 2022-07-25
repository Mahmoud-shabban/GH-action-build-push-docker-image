FROM python:3.8
LABEL maintainer="Mahmoud Shabban"

COPY . /app
WORKDIR /app
RUN python -m pip install -r requirements.txt

CMD [ "python3", "app.py" ]