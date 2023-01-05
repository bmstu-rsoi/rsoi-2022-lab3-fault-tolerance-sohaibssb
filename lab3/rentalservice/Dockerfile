FROM python

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY / /lab3/
WORKDIR /lab3

CMD ["python3", "main.py"]