FROM python:3.11-slim

LABEL author="mle-student"

COPY ./main.py ./my_super_dir/

WORKDIR my_super_dir

RUN pip install python-cowsay==1.1.0

CMD ["python3", "./main.py"]