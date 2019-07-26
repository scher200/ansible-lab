FROM williamyeh/ansible:debian9

RUN mkdir /root/.ssh
COPY ./ssh/config /root/.ssh/config
RUN chown -R root:root /root/.ssh
RUN chmod 600 /root/.ssh/config

