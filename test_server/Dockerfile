FROM python:alpine

WORKDIR /pytest/

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY *.py pytest.ini ./

CMD ["pytest"]
