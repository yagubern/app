FROM python:3.6
WORKDIR /app
ADD requirements.txt /app
RUN pip install -r requirements.txt
ADD . /app
EXPOSE  5000
ENV POST_DATABASE_HOST=post_db
ENTRYPOINT ["python3", "post_app.py"]
