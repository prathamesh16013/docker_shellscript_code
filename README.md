# docker_shellscript_code
nano myfile.sh
nano mydockerfile
docker build -f mydockerfile -t mysqlimg .
docker run -d -e MYSQL_ROOT_PASSWORD=Pass@123 mysqlimg
docker ps
docker exec -it e0dac12806ee bash
