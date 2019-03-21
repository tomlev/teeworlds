openfng_srv-linux64_0.09
https://www.teeworlds.com/forum/viewtopic.php?id=7868
REQUIRES TEEWORLD CLIENT 0.6 https://www.teeworlds.com/?page=downloads


docker build -t tleviandier/teeworlds-openfng .
docker run -p 8303:8303/udp tleviandier/teeworlds-openfng
docker push tleviandier/teeworlds-openfng
