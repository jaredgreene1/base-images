FROM resin/ccon-01-alpine-buildpack-deps:3.6-curl

RUN apk add --update \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/cache/apk/*
