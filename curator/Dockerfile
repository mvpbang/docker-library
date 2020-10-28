FROM registry.access.redhat.com/rhel7-minimal
MAINTAINER mvpbang@163.com
LABEL INFO="curator5 to delete elasticsearch indices"
ADD https://packages.elastic.co/curator/5/centos/7/Packages/elasticsearch-curator-5.8.1-1.x86_64.rpm /tmp/
RUN rpm -ivh elasticsearch-curator-5.8.1-1.x86_64.rpm && rm -rf /tmp/*