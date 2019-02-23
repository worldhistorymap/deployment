FROM ubuntu
RUN apt-get update && apt-get install -y \
	gunicorn \
	python3-pip \
	supervisor \
RUN pip3 install \
	TileStache \
	Pillow \
	modestmaps \
	simplejson \
	werkzeug \
	uuid \
	mbutil

