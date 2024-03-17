FROM python:3.13.0a5-alpine
COPY . /app
WORKDIR /app
RUN pip install flask flask_cors
EXPOSE 5000
CMD ["python", "app.py"]