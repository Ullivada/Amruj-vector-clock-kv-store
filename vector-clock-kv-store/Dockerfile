FROM python:3.13-slim

# Set working directory
WORKDIR /app

# Copy source code
COPY src/ .

# Install dependencies
RUN pip install flask requests

# Start the node script
CMD ["python", "src/node.py"]
