# Use the specified base image
FROM python:3.12-slim-bookworm

# Set the working directory
WORKDIR /workspace

# Install MkDocs and required plugins
RUN pip install mkdocs mkdocs-material mkdocs-glightbox

# Expose the port MkDocs will run on
EXPOSE 8000

# Set the default command to serve the MkDocs site
CMD ["mkdocs", "serve", "--dev-addr=0.0.0.0:8000"]
