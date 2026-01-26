FROM python:3.14-alpine3.22
WORKDIR /app
COPY  ./templates ./templates/
COPY ./app.py ./ 
COPY ./requirements.txt ./ 
RUN pip install -r requirements.txt
CMD ["python","app.py"]