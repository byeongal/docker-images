FROM byeongal/python:3.12.11-jammy-cuda12.6-cudnn-devel

# https://docs.astral.sh/uv/guides/integration/docker/#installing-uv
# Download the latest installer
ADD https://astral.sh/uv/install.sh /uv-installer.sh
# Run the installer then remove it
RUN sh /uv-installer.sh && rm /uv-installer.sh
# Ensure the installed binary is on the `PATH`
ENV PATH="/root/.local/bin/:$PATH"