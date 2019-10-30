FROM python:3.7

# Create app directory
WORKDIR /app

ENV PYTHON_ENV=production

# Install app dependencies
COPY ./requirements.txt ./

RUN pip install -r requirements.txt

# Bundle app source
COPY . /app

CMD [ "python", "app.py" ]