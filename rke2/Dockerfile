FROM centos:7

RUN curl -sfL https://get.rke2.io | sh -

RUN groupadd etcd
RUN useradd -m -u 1001 etcd -g etcd

ENTRYPOINT [ "rke2" ]

CMD [ "server" ]