FROM python:3.14.0a2-alpine
COPY . /app
WORKDIR /app
RUN pip install flask flask_cors
EXPOSE 5000
CMD ["python", "app.py"]