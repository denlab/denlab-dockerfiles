FROM debian:jessie

RUN apt-get update -y && apt-get install -y aptitude

RUN aptitude update -y 

RUN aptitude install -y python-pip

RUN pip install --upgrade pip

RUN aptitude install -y apt-file

RUN apt-file update

RUN aptitude install -y libpython2.7-dev

RUN pip install glances

CMD sleep infinity
