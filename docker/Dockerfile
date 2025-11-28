FROM python:3.13

WORKDIR /usr/local/app

COPY python/hello.py ./hello.py

# If using Flask:
RUN pip install flask

EXPOSE 8080

CMD ["python", "hello.py"]
