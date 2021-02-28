# run app from docker hub

docker run -p 13579:8080 -d abir1995/edurekanodejs

# browser

localhost:13579/getGithubUser/BatabyalAkash

# use another terminal to stop the running docker app

docker ps (to get container id)
docker stop <container id>
