FROM m0rf30/clearwater-base
MAINTAINER maintainers@projectclearwater.org
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y --force-yes clearwater-sip-stress-coreonly clearwater-snmp-alarm-agent clearwater-snmp-handler-astaire \
	clearwater-snmp-handler-bono clearwater-snmp-handler-cdiv clearwater-snmp-handler-chronos clearwater-snmp-handler-homestead clearwater-snmp-handler-sprout \
	clearwater-snmp-handler-memento-as clearwater-snmp-handler-memento clearwater-snmp-alarm-agent
EXPOSE 5052
EXPOSE 5054
