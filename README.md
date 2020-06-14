# 서버 세팅
## docker
docker run -d -e VIRTUAL_HOST=nginx-proxy를 위한 도메인 설정 --name django_cdci ubuntu:latest
## package
- apt-get update && apt-get upgrade
- apt-get install python3 python3-pip
- apt-get install apache2
- apt-get install libapache2-mod-wsgi-py3
- apt-get install libmysqlclient-dev -y