FROM python:3.6

ADD . /app
RUN pip install -r /app/requirements.txt

WORKDIR /app/

CMD python monitor.py
