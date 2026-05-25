FROM jupyter/scipy-notebook:latest

RUN pip install --upgrade pip

RUN pip install \
    mlflow \
    boto3 \
    scikit-learn \
	s3fs \
	pyarrow \
    pandas \
    fastapi \
    uvicorn \
    typing_extensions==4.12.2 \
	psycopg2-binary \
	sqlalchemy
