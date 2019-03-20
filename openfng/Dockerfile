FROM ubuntu

COPY run.sh /run.sh
RUN chmod +x /run.sh

RUN mkdir /teeworlds
COPY ./content/* /teeworlds/
RUN chmod +x /teeworlds/openfng_srv-linux64_0.09

EXPOSE 8303/udp
CMD ["/run.sh"]
