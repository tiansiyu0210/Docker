FROM debian:buster
RUN cd /etc/apt && touch apt.conf && echo "Acquire::http::Proxy \"http://atl1webproxlb.corp.secureworks.net:3128\";" > apt.conf  && apt-get update  && apt-get install -y git

