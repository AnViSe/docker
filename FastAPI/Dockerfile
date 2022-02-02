FROM python:3.10

RUN mkdir -p /usr/src/app/
WORKDIR /usr/src/app/

COPY /app/ /usr/src/app/
RUN pip install --no-cache-dir fastapi uvicorn

EXPOSE 8000

CMD ["python", "main.py"]
