FROM python:3.9-slim
COPY . /devalore
RUN sudo pip install --no-cache-dir -r devalore/requirements.txt && cd devalore
CMD sudo pytest