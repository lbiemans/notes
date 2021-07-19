# notes

# Debug ssl
openssl s_client -showcerts -connect www.microsoft.com:443 <br />
See: http://movingpackets.net/2015/03/16/five-essential-openssl-troubleshooting-commands/<br />
<br />
#Docker stuff<br />
DOCKER_BUILDKIT=1 docker build --cpuset-cpus 0-7 . <br />
docker ps<br />
docker system prune<br />
