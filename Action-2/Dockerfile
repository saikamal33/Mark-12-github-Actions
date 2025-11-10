# use official pyhton slim
FROM python:3.11-slim

WORKDIR /app

# Copy files
COPY requirement.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

# Expose Port

EXPOSE 5000
CMD ["python", "app.py"]

