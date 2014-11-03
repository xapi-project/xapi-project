xapi-project
============

The [xapi toolstack](http://www.xenproject.org/developers/teams/xapi.html)
- manages clusters of Xen hosts as single entities
- allows running VMs to be migrated between hosts (including with storage)
  with minimal downtime
- automatically restarts VMs after host failure ("High Availability")
- facilitates disaster recovery cross-site
- simplifies maintainence through rolling pool upgrade
- collects performance statistics for historical analysis and for alerting
- has a full-featured XML-RPC based API, used by clients such as
  [XenCenter](https://github.com/xenserver/xenadmin),
  [Xen Orchestra](https://xen-orchestra.com),
  [OpenStack](http://www.openstack.org)
  and [CloudStack](http://cloudstack.apache.org)

The xapi toolstack is developed by the
[xapi project](http://www.xenproject.org/developers/teams/xapi.html):
a sub-project of the Linux Foundation Xen Project.

Contents
--------

- [Architecture](architecture/README.md): read about how the components of the
  xapi toolstack work together
- [Features](features/README.md): learn about the features supported by xapi and
  how they work.
- [Xen API documentation]((https://xapi-project.github.io/xen-api/): explore
  the Xen API
- [Futures](futures/README.md): find out how Xenopsd is likely to change and
  how you can help.
- [Github Wiki](https://github.com/xapi-project/xapi-project/wiki): explore the
  local wiki on github
- [Xen project Wiki](http://wiki.xenproject.org/wiki/XAPI): explore the xapi
  section of the Xen wiki
