# Gunakan base image Python
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy file aplikasi ke dalam container
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Jalankan aplikasi Flask
CMD ["python", "app.py"]
