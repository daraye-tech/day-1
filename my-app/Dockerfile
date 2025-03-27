FROM python:3.12-slim

WORKDIR /app

# copy the requirements file used for dependencies
COPY . .

# Install Python dependencies
RUN pip install --upgrade pip && \
    pip install -r requirements.txt

# cmd to launch app when container is run
CMD [ "python", "app.py" ]