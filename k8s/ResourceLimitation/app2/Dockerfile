FROM python:3.13.0rc2-slim
RUN apt-get update -y
RUN apt-get install stress-ng -y
COPY ./app /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["python", "app.py"]