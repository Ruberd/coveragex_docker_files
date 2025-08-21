# coveragex_docker_files

#build
docker-compose up --build

#to start frontend
docker-compose up -d react-frontend

#to start backend
docker-compose up -d service-coveragex

#to start databases
docker-compose up -d mysql-workbench
docker-compose up -d mysql

#check logs
docker logs react-frontend
docker logs service-coveragex