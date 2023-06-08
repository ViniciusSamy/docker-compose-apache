FROM httpd:2.4

RUN apt-get update
RUN apt-get install wget unzip

WORKDIR /tmp/site-content

RUN wget "https://www.tooplate.com/zip-templates/2134_gotto_job.zip"
RUN unzip "2134_gotto_job.zip"
RUN cp -r 2134_gotto_job/*  /usr/local/apache2/htdocs/

RUN rm -r /tmp/site-content

EXPOSE 80