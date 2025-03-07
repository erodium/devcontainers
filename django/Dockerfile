FROM python:3.12
WORKDIR /app
RUN pip install django psycopg
COPY . ./
ENTRYPOINT ["python3", "manage.py"]