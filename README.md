# docker_crontab


#build image:
docker build -t hello-cron .

#run container:
docker run -d --name hello-cron-container hello-cron


#check logs
docker logs hello-cron-container
