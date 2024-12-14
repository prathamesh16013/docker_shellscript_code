# docker_shellscript_code
we can create a new database using docker shellscript to create to files
one is myfile.sh and mydockerfile. and execute the file.

nano myfile.sh
nano mydockerfile
docker build -f mydockerfile -t mysqlimg .
docker run -d -e MYSQL_ROOT_PASSWORD=Pass@123 mysqlimg
docker ps
docker exec -it cont-id or nsme /bin/bash
