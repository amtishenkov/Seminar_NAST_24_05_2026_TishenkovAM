# Seminar_NAST_24_05_2026_TishenkovAM

Jupyther http://localhost:8888?token=12345
Superset http://localhost:8088/
MinIO http://localhost:9001/

Database Superset
Host: PostgreSQL
Port: 5432
Database name: ml_db
Username: ml_user
Password: ml_user

Superset
Login: admin
Password: admin

postgresql+psycopg2://ml_user:ml_user@postgresql:5432/ml_db

dashboards - dashboards для импорта в Superset

notebooks/Pipeline.ipynb - основной ноутбук Jupyter