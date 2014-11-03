Architecture
============

The Xapi toolstack manages a cluster of hosts, network switches and storage
on behalf of clients such as
[XenCenter](https://github.com/xenserver/xenadmin),
[Xen Orchestra](https://xen-orchestra.com),
[OpenStack](http://www.openstack.org)
and [CloudStack](http://cloudstack.apache.org).

The most fundamental concept is of a *Resource pool*: the whole cluster
managed as a single entity. The following diagram shows a cluster of hosts
running xapi, all sharing some storage:

![A Resource Pool](http://xapi-project.github.io/xapi-project/doc/architecture/pool.png)

... describe diagram ...

The following diagram shows the software running on a single host. Note that
all hosts run the same software.

![A Host](http://xapi-project.github.io/xapi-project/doc/architecture/host.png)

... describe diagram ...
