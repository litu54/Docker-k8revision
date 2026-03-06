FROM python:3.9-slim

WORKDIR /app

ADD app.py app.py 

RUN pip install flask 

EXPOSE 5000 

# Defines the default command to start the application.
CMD ["python", "app.py"]