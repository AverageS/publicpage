FROM python:3


#install depends
RUN pip install flask

RUN apt-get update -y

RUN apt-get install -y poppler-utils
# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
ADD . /app

CMD python3 server.py
#add entrypoint

