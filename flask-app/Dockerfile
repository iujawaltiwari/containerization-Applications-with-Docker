# Get Base image with python 3.9

FROM python:3.9

# Your working directory

WORKDIR /app

# Copy the source code to the workdir in container

COPY . .

# Install all required all dependencies

RUN pip install -r requirements.txt

# Run the python app

CMD ["python","run.py"]

