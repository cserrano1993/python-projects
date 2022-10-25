FROM python:alpine3.16
RUN pip3 install --upgrade pip
WORKDIR /APLICACION
COPY . /APLICACION/
RUN pip3 --no-cache-dir install -r requirements.txt
CMD [ "python3", "src/app.py" ]