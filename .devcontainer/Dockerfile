# Use the official Python image from the Docker Hub
FROM python:3.12

# Install system dependencies
RUN apt-get update && apt-get install -y \
    python3-opencv

# Install Python dependencies
RUN pip install --upgrade pip
RUN pip install \
    jupyter \
    matplotlib \
    numpy \
    opencv-python

# Set the default command to run Jupyter Notebook
CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--no-browser", "--allow-root"]
