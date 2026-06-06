FROM python:3.11
RUN pip install --disable-pip-version-check --progress-bar off flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 8080
CMD python /home/myapp/sample_app.py
