FROM python:3
LABEL "AUTHOR"="Nikhil"
LABEL "PROJECT"="EFT"

WORKDIR /app
COPY . /app

RUN pip install flask flask_cors
EXPOSE 1003

CMD ["python","index.py"]