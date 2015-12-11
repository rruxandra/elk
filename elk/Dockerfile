FROM sebp/elk

MAINTAINER ruxandra.laceanu@payu.ro

ADD etc/logstash/conf.d/02-beats-input.conf /etc/logstash/conf.d/02-beats-input.conf

ADD etc/logstash/conf.d/GeoIP.dat /etc/logstash/conf.d/GeoIP.dat

EXPOSE 5044
