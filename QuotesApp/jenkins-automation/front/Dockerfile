FROM python:3.6
WORKDIR /app
ADD . .
RUN pip3 install -r requirements.txt
EXPOSE 3001
CMD ["python3", "front.py"]