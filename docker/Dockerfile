FROM python:3.7-stretch

WORKDIR /jnotebook_reader

COPY . .

RUN pip install -r requirements.txt

RUN chmod +x ./docker/docker-entrypoint.sh

CMD ["./docker/docker-entrypoint.sh"]