from python

RUN pip install flask
RUN mkdir -p /app

WORKDIR /app

ADD . /app

EXPOSE 5000
CMD ["bash", "-c", "python api.py"]
