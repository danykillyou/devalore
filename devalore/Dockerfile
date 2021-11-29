FROM python:3.9-slim
COPY . /devalore
RUN pip install --no-cache-dir -r devalore/requirements.txt && cd devalore
CMD pytest