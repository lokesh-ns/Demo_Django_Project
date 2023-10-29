FROM "python:latest"
RUN apt-get install -y python3.10
WORKDIR /opt
COPY . .
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python3", "manage.py", "runserver", "0.0.0.0:8000"]