FROM python:3.14.3-alpine
WORKDIR /app
COPY . . 
RUN pip install requests
ENTRYPOINT ["python"]
CMD ["app.py"]
