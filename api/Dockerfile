FROM python:3.7
ADD ./api /api
WORKDIR /api
EXPOSE 5000
RUN pip3 install -r requirements.txt
ENTRYPOINT ["python3","api.py"]
