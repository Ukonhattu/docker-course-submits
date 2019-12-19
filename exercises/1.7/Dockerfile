FROM ubuntu:16.04

WORKDIR /usr/app
RUN apt-get update && apt-get install -y curl
COPY curl_script.sh .
RUN chmod +x ./curl_script.sh
CMD ./curl_script.sh

#run with docker run -it culer
#(if you have tagged the build as curler)
