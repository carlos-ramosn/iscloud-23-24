FROM python:3.8-slim-buster
WORKDIR /app
COPY app.py app.py
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
EXPOSE 5002
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
ENV MYSQL_ROOT_PASSWORD=p@ssw0rd1