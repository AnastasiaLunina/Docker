FROM python

COPY ./requirements.txt /src/requirements.txt

RUN pip3 install --no-cache-dir --upgrade -r /src/requirements.txt

COPY . /src

EXPOSE 8000

WORKDIR src

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]