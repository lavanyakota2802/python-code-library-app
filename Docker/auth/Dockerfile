FROM python:3.14-alpine3.22
WORKDIR /app
COPY auth/* .
RUN pip install -r requirements.txt
CMD ["python","auth_service.py"]