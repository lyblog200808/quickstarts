FROM python:3.13.0b3-alpine
COPY . /app
WORKDIR /app
RUN pip install flask flask_cors
ENTRYPOINT ["python"]
EXPOSE 5000
CMD ["app.py"]
