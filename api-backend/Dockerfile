FROM ubuntu:latest
RUN apt update
RUN apt install -y python python-flask python-requests
COPY api.py /app/api.py
CMD ["python", "/app/api.py"]
