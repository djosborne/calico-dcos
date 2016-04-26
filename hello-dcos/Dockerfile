FROM python:slim
RUN pip install flask redis
ADD webserver.py .
CMD ["python", "webserver.py"]
