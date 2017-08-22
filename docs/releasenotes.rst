#########################################
Release notes
#########################################

^^^^^^^^^^^^
Requirements
^^^^^^^^^^^^

* Splunk 6.x / Universal Forwarder v6.x and later Only

* Universal Forwarders clients system lacking a Python 2.7.x interpreter requires Perl WITH Time::HiRes module available

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
What has been fixed by release
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

========
V1.3.32:
========

- fix: Python parser - header detection correction for nmon external monitoring
- feature: Add df information for improved file system monitoring and storage capacity planning

========
V1.3.32:
========

- fix: Python parser - preserve data ordering when possible during key value transformation
- feature: eventgen implementation (2 AIX and 2 Linux servers with stress load on systems)

========
V1.3.31:
========

- fix: Python parser issue - epoch time stamp incorrectly parsed for dynamic data #1

========
V1.3.30:
========

- fix: check curl availability in hec_wrapper.sh
- fix: redirect to null any curl stderr/stdout in hec_wrapper.sh
- fix: missing log_date function in hec_wrapper.sh

========
V1.3.29:
========

*Notes: This is the first version of the TA-nmon-hec, for practical purposes and because it shares most of the components, the TA-nmon-hec follows the TA-nmon version*

- First release of the TA-nmon-hec
