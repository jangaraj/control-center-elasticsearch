Elasticearch Control Center template
=====================================

[Dockerized Elasticsearch](http://www.elastic.co) cluster
template for [Zenoss Control Center](http://controlcenter.io/)

[![Paypal donate button](http://jangaraj.com/img/github-donate-button02.png)]
(https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8LB6J222WRUZ4)

Installation
============

- Import provided template
- Deploy Elasticsearch Application
- Start and use it - default vhost elasticsearch


Adding nodes to the cluster
===========================

Simply edit the service and increase the number of instances in the Control
Center UI. The new nodes will automatically join the cluster.

Compiling and adding the template
=================================

Add the service template to your Control Center installation:

```
serviced template compile elasticsearch | serviced template add
```

Author
======

[Devops Monitoring zExpert](http://www.jangaraj.com 'DevOps / Docker / Zabbix / Zenoss / Monitoring'), who loves monitoring 
systems, which start with letter Z. Those are Zabbix and Zenoss.

Professional monitoring services:

[![Monitoring Artist](http://monitoringartist.com/img/github-monitoring-artist-logo.jpg)]
(http://www.monitoringartist.com 'DevOps / Docker / Zabbix / Zenoss / Monitoring')
