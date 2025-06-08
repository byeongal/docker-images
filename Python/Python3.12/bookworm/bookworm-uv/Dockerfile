FROM python:3.12.11-bookworm

ENV UV_INSTALL_DIR=/opt/uv
ENV PATH="${UV_INSTALL_DIR}/bin:${PATH}"

# https://docs.astral.sh/uv/reference/installer/#changing-the-install-path
RUN curl -LsSf https://astral.sh/uv/install.sh | sh