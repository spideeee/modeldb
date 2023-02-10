FROM python:3.12.0a5-alpine

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY model.pkl .
COPY predictor.py .

CMD ["python", "predictor.py"]