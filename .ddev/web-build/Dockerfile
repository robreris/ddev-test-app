RUN curl -L https://github.com/gohugoio/hugo/releases/download/v0.140.2/hugo_0.140.2_Linux-64bit.tar.gz | tar -xz && mv hugo /usr/local/bin/

ADD https://github.com/FortinetCloudCSE/CentralRepo.git#main /home/CentralRepo

WORKDIR /home/CentralRepo

#RUN git submodule update --init --recursive

#RUN apt-get install python3 && ln -sf python3 /usr/bin/python

#ENTRYPOINT ["/home/CentralRepo/scripts/local_copy.sh"]
