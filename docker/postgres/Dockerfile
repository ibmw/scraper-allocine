FROM postgres:11

ARG POSTGRES_USER
ENV POSTGRES_USER ${POSTGRES_USER}

ARG POSTGRES_PASSWORD
ENV POSTGRES_PASSWORD ${POSTGRES_PASSWORD}

ARG PGPASSWORD
ENV PGPASSWORD ${PGPASSWORD}

COPY ./docker/postgres/init.sql /docker-entrypoint-initdb.d/
