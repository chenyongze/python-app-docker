FROM python:alpine3.16
ADD . /app/wwwroot
WORKDIR /app
RUN cd /app/wwwroot \
    && pip install -r requirements.txt
# CMD ["python", "/app/wwwwroot/app.py"]