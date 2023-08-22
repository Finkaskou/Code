FROM ubuntu

RUN apt-get update
RUN apt-get install -y wget apache2

COPY page2.html /var/www/html/ 
COPY index.html /var/www/html/ 
RUN systemctl start apache2
ENTRYPOINT ["/bin/bash"]