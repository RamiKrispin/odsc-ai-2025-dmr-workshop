FROM docker.io/rkrispin/python-base:0.0.1

# Arguments
ARG PYTHON_VER="3.11"
ARG VENV_NAME="my_project"
ARG RUFF_VER="0.12.0"

# Environment variables
ENV VENV_NAME=$VENV_NAME
ENV PYTHON_VER=$PYTHON_VER
ENV RUFF_VER=$RUFF_VER

# Set Python environment
COPY install_uv.sh requirements.txt tmp/
RUN bash ./tmp/install_uv.sh 
RUN SNIPPET="export PROMPT_COMMAND='history -a' && export HISTFILE=/root/.zsh_history && export HISTIGNORE='ls'" \
    && echo "export HISTFILESIZE=1000" >> "/root/.zshrc"\
    && echo "$SNIPPET" >> "/root/.zshrc"