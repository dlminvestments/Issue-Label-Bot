FROM python:3.13.2-slim

RUN pip install numpy pandas scikit-learn dill tensorflow dask ktext distributed dask-ml
RUN mkdir /data
RUN mkdir /output
ENV PYTHONUNBUFFERED=0
COPY src /src
