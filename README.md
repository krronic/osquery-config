# osquery-config

Tested on - Ubuntu 20.04.1

This respository contains osquery configuration, flags and sample query packs. Tested on Ubuntu 20.04.1, no gurantees, use at your own risk.

#### conf/osquery.flags => /etc/osquery/osquery.flags
Initialization and configuration flags. 


#### conf/osquery.conf => /etc/osquery/osquery.conf
Configuration including query packs.


#### query-packs/monitoring-queries.conf => /opt/osquery/share/osquery/packs/monitoring-queries.conf
syslog, file, process, socket and user evenr monitoring queries.


#### splunk-uef/inputs.conf => /opt/splunkforwarder/etc/system/local/inputs.conf
Splunk univerversal forwarder configuration.


#### splunk-uef/props.conf => /opt/splunkforwarder/etc/system/local/props.conf
json event properties for consumption by splunk
