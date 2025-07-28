FROM python:3.14.0rc1-alpine3.22
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
