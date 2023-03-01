# Insert your Dockerfile here.
FROM ubuntu:22.04

# Install python3
RUN apt update && apt upgrade -y && apt install -y python3

COPY index.html /var/www/index.html

WORKDIR /var/www/

EXPOSE 8000

CMD ["python3", "-m", "http.server", "8000"]