FROM mesos
MAINTAINER RedJack, LLC

# Mesos fetcher uses unzip to extract staged zip files

RUN \
  apt-get install -y unzip && \
  apt-get install -y python && \
  apt-get install -y python-pip && \
  apt-get install -y python-numpy  && \
  apt-get install -y python-scipy  && \
  apt-get clean

EXPOSE 5051
CMD ["mesos-slave"]
