FROM python:3.10-slim
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

COPY {{cookiecutter.project_slug}} ./{{cookiecutter.project_slug}}
ENV PYTHONPATH=/usr/src/app

RUN useradd -M -s /bin/bash {{cookiecutter.project_slug}} && chown -R {{cookiecutter.project_slug}}:{{cookiecutter.project_slug}} /usr/src/app
USER {{cookiecutter.project_slug}}

CMD [ "python", "{{cookiecutter.project_slug}}/main.py" ]
