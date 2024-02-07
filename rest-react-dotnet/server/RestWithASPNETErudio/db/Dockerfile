FROM mysql:8.3.0
EXPOSE 3308
COPY ./RestWithASPNETErudio/db/migrations/ /home/database/
COPY ./RestWithASPNETErudio/db/dataset/ /home/database/
COPY ./RestWithASPNETErudio/ci/init_database.sh /docker-entrypoint-initdb.d/init_database.sh