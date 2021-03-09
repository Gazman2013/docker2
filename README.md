# docker2
lwsson two
 docker images
545  docker run -it centos:latest /bin/bash
546*
547  docker run -it centos:latest /bin/bash
548  docker run -d -p 80:8580 nginx
549  curl localhost:80
550  ps -a
551  ps
552  netstat -antp
553  docker run -d -p 80:8085 nginx
554  curl localhost:8580
555  ps
556  docker ps
557  docker run 22610d86b041
558  docker run -it 22610d86b041
559  docker run -it nginx
560  clear
561  curl localhost:8580
562  docker login
563  docker images
564  docker ps
565*
  566  docker --help
  567  docker run -d -p 80:8580 nginx
  568  docker ps
  569*
  570  docker ps
  571  docker top v2d64c7af36a1
  572  docker top nginx
  573  docker stop nginx
  574  docker run -d -p --name train training/webapp python app.ry
  575  docker run -d -P --name train training/webapp python app.ry
  576  docker ps -l
  577  docker inspect train
  578  docker inspect train|grep train
  579  docker stop train
  580  docker rm train
  581  docker network ls
  582  docker run -itd --name=networtest ubuntu
  583  docker network inspect brige
  584  docker networktest inspect brige
  585  docker networtest inspect brige
  586  docker networtest inspect bridge
  587  docker run -itd --name=networktest ubuntu
  588  docker networktest inspect bridge
  589  docker inspect netwoktwst bridge
  590  docker network create -d bridge my-bridge-network
  591  docker network ls
  592  docker network ispect my-bridge-network
  593  docker network inspect my-bridge-network
  594  docker run -d --network=my-bridge-network --name db training/postgres
  595  docker ps
  596  docker inspect --format='{{json .NetworkSettings.Networks}}'  db
  597  docker run -d --name web training/webapp python app.py
  598  docker inspect --format='{{json .NetworkSettings.Networks}}'  web
  599  docker exec -it db bash
  600  docker network connect my-bridge-network web
  601  docker exec -it db bash
  602  docker network ls
  603  docker ps
  604* docker exec -it
  605  docker exec -it nginx
  606  docker exec -it interesting_hermann bash
  607  cd /home
  608  docker run -d _p --name web -v /webapp training/webapp python app.py
  609  docker stop web
  610  docker rm web
  611  docker run -d _p --name web -v /webapp training/webapp python app.py
  612  docker run -d -P --name web -v /webapp training/webapp python app.py
  613  VOLUME
  614  docker inspect web
  615  docker stop web
  616  docker rm web
  617  docker run -d -P --name web -v /webapp training/webapp python app.py
  618  docker ps
  619  ls
  620  cd rodionov_gazman2013/
  621  ls -la
  622  ls
  623  docker image
  624  docker images
  625  docker create -v /dbdata --name dbstore training/postgres /bin/true
  626  docker ps
  627  docker run -d --volume-from --name db1 training/postgres
  628  docker run -d --volume-from dbstore --name db1 training/postgres
  629  docker run -d --volumes-from dbstore --name db1 training/postgres
  630  docker run -d --volumes-from dbstore --name db2 training/postgres
  631  docker run -d --volumes-from dbstore --name db3 training/postgres
  632  docker run -d --name db4 --volumes-from db1 training/postgres
  633  docker ps
  634  df -h
  635  docker stop db1
  636  docker volume ls
  637  docker volume ls -f dangling=true
  638  docker run --rm --volumes-from dbstore -V $(pwd):/backup ubuntu tar cvf /backup/backup.tar /dbdata
  639  docker run --rm --volumes-from dbstore -v $(pwd):/backup ubuntu tar cvf /backup/backup.tar /dbdata
  640  ls
  641  docker run --help
  642  clear
  643  atp install docker-compose
  644  apt install docker-compose
  645  mkdir composetest
  646  cd composetest/
  647  nano app.py
  648  nano requirements.txt
  649  nano Dockerfile
  650  nano requirements.txt
  651  nano Dockerfile
  652  nano docker-compose.yaml
  653  ls
  654  docker-compose up
  655  nano docker-compose.yaml
  656  docker-compose up
  657  ls
  658  nano app.py
  659  nano app.py
  660  docker-compose up
  661  nano app.py
  662  history
