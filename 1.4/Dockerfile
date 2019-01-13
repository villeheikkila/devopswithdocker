FROM ubuntu:16.04 

WORKDIR /mydir 
COPY script.sh .
RUN apt-get update && apt-get install -y curl
RUN chmod +x script.sh 
CMD ["/bin/bash"]
CMD bash script.sh

