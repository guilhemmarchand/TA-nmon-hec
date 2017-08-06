###
FAQ
###

**Can I have my own nmon collection while running the TA-nmon-hec ?**

The answer is no, and this won't be supported.

For foot print optimization purposes, the TA-nmon-hec has his own workflow which implements the so called "fifo mode".

**Can I have the TA-nmon-hec and the TA-Unix in the same time ?**

You might need the TA-unix for specific tasks that are out of the scope of the Nmon application, such as ingesting security related data.

Running both addons in same servers is not a problem at all.

The TA-nmon-hec is CIM compatible, for most performance related metrics, the TA-nmon-hec can be transparently used in replacement of the TA-Unix.

**Can I have the TA-nmon-hec and the TA-nmon in the same time ?**

The answer is no.

You must run either the TA-nmon, or the TA-nmon-hec. Both TAs share the same parsing configuration.

**Is the TA-nmon-hec CIM compatible ?**

Yes it is. The TA-nmon-hec is CIM compatible, it will specially deal with the following CIM data models:

- Application State
- Inventory
- Network Traffic
- Performance

If you are an Enterprise Security customer for instance, all you need is having the TA-nmon deployed in search heads as well.
