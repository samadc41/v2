FROM python:3.8-slim-buster
WORKDIR /auth
COPY . .
RUN pip install wheel
RUN pip install -r requirements.txt
RUN pip install gunicorn 
CMD ["python", "manage.py", "runserver"]
