FROM centos:7

RUN yum install -y epel-release

RUN yum makecache fast

RUN yum install -y python-pip

RUN yum install -y gcc python-devel

RUN pip install --upgrade pip 

RUN pip install bottle 
RUN pip install requests 
RUN pip install batinfo 
RUN pip install zeroconf
RUN pip install netifaces
RUN pip install pymdstat
RUN pip install influxdb
RUN pip install elasticsearch
RUN pip install potsdb
RUN pip install statsd 
RUN pip install pystache
RUN pip install docker-py 
RUN pip install pysnmp
RUN pip install pika
RUN pip install py-cpuinfo
RUN pip install bernhard
RUN pip install scandir

RUN pip install glances

ENTRYPOINT ["glances"]
