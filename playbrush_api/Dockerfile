FROM python:3.7
RUN mkdir /usr/src/app/
COPY . /usr/src/app/
WORKDIR /usr/src/app/
RUN pip install -r requirements.txt
CMD ["python", "app.py"]
