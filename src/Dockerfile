FROM python:3.11-bullseye
RUN pip install Flask
RUN pip install Flask-Login
RUN pip install Flask-SQLAlchemy
COPY . /opt/app
WORKDIR /opt/app
CMD [ "python", "./app.py" ]