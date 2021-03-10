FROM python:rc-alpine3.12
RUN mkdir /app
WORKDIR /app
RUN ls -ltr
RUN pwd
ADD * /app/
RUN ls -ltr
RUN ls -ltr python
RUN pip install -r python/app/requirements.txt
EXPOSE 5000
CMD ["python", "/app/main.py"]