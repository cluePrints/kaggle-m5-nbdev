FROM fastai/codespaces
RUN apt-get update \
 && apt-get install libxml2-dev libxslt1-dev python3-dev \
    unzip -y \
 && rm -rf /var/lib/apt/lists/* \
 && pip install --upgrade pip
