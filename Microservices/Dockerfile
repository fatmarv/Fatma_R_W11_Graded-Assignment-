FROM python:3-alpine3.17
WORKDIR /dockerapp
COPY  . /dockerapp/
RUN pip install --trusted-host pypi.python.org -r requirements.txt
EXPOSE 5050
CMD ["python", "app"]