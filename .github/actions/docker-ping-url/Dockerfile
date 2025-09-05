FROM python:alpine3.19

WORKDIR /app

COPY requirements.txt .

RUN python -Vu
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python", "/app/main.py" ]