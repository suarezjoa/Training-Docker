FROM python:3.12-alpine

RUN apk add
#directoriod
WORKDIR /app 

COPY . /app/

# instalar librerias 
RUN pip install --no-cache-dir -r requirements.txt 

EXPOSE 80

CMD ["python", "app.py"]