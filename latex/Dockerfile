FROM ubuntu

ADD latex/01_nodoc /etc/dpkg/dpkg.cfg.d/01_nodoc

RUN apt-get -y update && apt-get install -y \
biber \
curl \
texlive-full \
git \
gnuplot \
python-matplotlib \
make \
&& apt-get clean \
&& rm -rf /var/lib/apt/lists/*
