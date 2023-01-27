FROM python:3.6.8
RUN mkdir -p /home/app
COPY . /home/app
RUN pip3 install -r /home/app/requirements.txt
EXPOSE 5000
CMD ["python3", "/home/app/src/index.py"]