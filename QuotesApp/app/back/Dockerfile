FROM python:3.6
WORKDIR /app
COPY . .
RUN pip3 install -r requirements.txt
EXPOSE 3000
CMD ["python3", "back.py"]