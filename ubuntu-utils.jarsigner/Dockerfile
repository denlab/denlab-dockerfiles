FROM denlab/ubuntu-utils

# java keystore stuff

## Create key
RUN bash -c 'echo -e "denisdenis\ndenisdenis\n\n\n\n\n\n\nyes\n\n" | keytool -genkey -alias denis'
## sign some jar
RUN cp /usr/lib/jvm/java-8-openjdk-amd64/lib/dt.jar .
##  with the key
RUN bash -c 'echo -e "denisdenis\n" | jarsigner dt.jar denis'
