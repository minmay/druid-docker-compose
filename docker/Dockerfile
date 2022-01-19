FROM apache/druid:0.22.1

RUN mkdir /opt/druid/conf/broker
RUN mkdir /opt/druid/conf/coordinator
RUN mkdir /opt/druid/conf/historical
RUN mkdir /opt/druid/conf/middlemanager
RUN mkdir /opt/druid/conf/overlord

COPY conf/druid/broker.properties /opt/druid/conf/broker/
COPY conf/druid/coordinator.properties /opt/druid/conf/coordinator/
COPY conf/druid/historical.properties /opt/druid/conf/historical/
COPY conf/druid/middle-manager.properties /opt/druid/conf/middlemanager/
COPY conf/druid/overlord.properties /opt/druid/conf/overlord/
