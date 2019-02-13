FROM redis:4.0.10
ENV POSTGRES_USER docker
ENV POSTGRES_PASSWORD docker
ENV POSTGRES_DB docker
#for each sql file in docker-entrypoint-initdb.d run the file
ADD CreateDB.sql /docker-entrypoint-initdb.d/