FROM python:3.8

COPY ./requirements.txt /webapp/requirements.txt

RUN pip install -r requirements.txt
RUN pip install flask

COPY webapp/* /webapp

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]