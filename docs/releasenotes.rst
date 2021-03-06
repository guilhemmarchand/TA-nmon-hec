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
V1.3.37:
========

- fix: nmon_helper.sh is referring to TA-nmon #10

========
V1.3.36:
========

- fix: OpenSSL lib issues on full Splunk instances #9

========
V1.3.35:
========

- feature: Solaris - SARMON upgrade to v1.12 (Sparc FIFO mode) #6
- fix: Rename eventgen.conf to avoid splunkd WARN messages #7

========
V1.3.34:
========

- feature: Solaris - SARMON upgrade to v1.12 (Sparc FIFO mode) #6

========
V1.3.34:
========

- fix: reactivating the JFSFILE / JFSINODE collections until new core release is available to prevent missing features

========
V1.3.33:
========

- fix: Python parser - header detection correction for nmon external monitoring
- fix: Perl parser issue - UARG parsing issue for AIX #2
- fix: unexpected operator issue during process identification #3
- fix: prevent bundle validation warn messages with spec files in README directory
- feature: Add df information for improved file system monitoring and storage capacity planning
- feature: JFSFILE/JFSINODE are being replaced (and deactivated) by external collection with DF_STORAGE/DF_INODES

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
