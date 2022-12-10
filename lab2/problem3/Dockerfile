FROM python:3-onbuild
RUN  pip install --upgrade pip 
COPY . /usr/src/app
RUN pip install -r requirements.txt
CMD ["python","app.py"]