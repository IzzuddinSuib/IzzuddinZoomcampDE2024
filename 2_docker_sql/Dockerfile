FROM python:3.9

RUN pip pyarrow
RUN pip install pandas

WORKDIR /app

COPY pipeline.py pipeline.py

ENTRYPOINT [ "bash" ]
