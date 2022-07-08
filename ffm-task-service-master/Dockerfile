# FROM python:3.7
FROM python:3.8-slim-bullseye
#RUN apk update && apk add libffi-dev postgresql-dev gcc python3-dev musl-dev
WORKDIR /task
COPY . .
COPY requirements.txt /task
RUN pip install -r requirements.txt
CMD ["python", "manage.py", "runserver"]

