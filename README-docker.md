Run using docker:
docker run -it --rm --mount "type=bind,src=~/.newsboat,target=/home/builder/.newsboat" lsemenenko/newsboat

Run using docker-compose:
docker-compose run --rm newsboat