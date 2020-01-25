curdir := $(shell pwd)
pdf:
	docker run --rm -v $(curdir):/workdir paperist/alpine-texlive-ja uplatex report.tex; \
	docker run --rm -v $(curdir):/workdir paperist/alpine-texlive-ja dvipdfmx report.dvi; \