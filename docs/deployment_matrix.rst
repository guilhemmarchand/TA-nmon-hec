#################
Deployment Matrix
#################

What goes where ?
-----------------

* The TA-nmon-hec is available for download as an independent application in Splunk base: https://splunkbase.splunk.com/app/

* The TA-nmon-hec is also available for download in its Git repository: https://github.com/guilhemmarchand/TA-nmon-hec

**Standalone deployment: A single Splunk instance does all**

+------------------------+---------------+
| Splunk Instance        | TA-nmon-hec   |
| (role)                 |               |
+========================+===============+
| Standalone             | X (optional)  |
+------------------------+---------------+

*The TA-nmon-hec provides nmon performance and configuration collection for the host than runs the add-on, which is optional*

**Distributed deployment:**

+--------------------------------------------+---------------------+
| Splunk Instance                            | TA-nmon-hec         |
| (role)                                     |                     |
+============================================+=====================+
| Search head (single instance or clustered) |    X (optional)     |
+--------------------------------------------+---------------------+
| Indexer (single instance or clustered)     |                     |
+--------------------------------------------+---------------------+
| Master node                                |    X (optional)     |
+--------------------------------------------+---------------------+
| Deployment servers                         |    X (optional)     |
+--------------------------------------------+---------------------+
| Heavy Forwarder                            |    X                |
+--------------------------------------------+---------------------+
| Universal Forwarder                        |    X                |
+--------------------------------------------+---------------------+

*The TA-nmon-hec provides nmon performance and configuration collection for the host than runs the add-on, which is optional*
