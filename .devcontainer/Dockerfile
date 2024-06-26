# Use the specified base image
FROM python:3.12-slim-bookworm

# Set the working directory to the root of the repository
WORKDIR /workspace

# Install Git
RUN apt-get update && apt-get install -y git && rm -rf /var/lib/apt/lists/*

# Copy the content of the repository to the working directory
COPY . /workspace

# Install MkDocs and required plugins
RUN pip install mkdocs mkdocs-material mkdocs-glightbox

# Expose the port MkDocs will run on
EXPOSE 8000

# Set the default command to serve the MkDocs site
CMD ["mkdocs", "serve", "--dev-addr=0.0.0.0:8000"]