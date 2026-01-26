FROM python:3.14-alpine3.22
WORKDIR /app
COPY ./barrow/* ./
RUN pip install -r requirements.txt
CMD ["python","borrow_service.py"]