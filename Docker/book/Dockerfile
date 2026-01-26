FROM python:3.14-alpine3.22
WORKDIR /app
COPY ./book/* ./
RUN pip install -r requirements.txt
CMD ["python","book_service.py"]