MTP-XPCOM
==========

Media Transfer Protocol (MTP) Device Services Extension with 
XPCOM (Cross Platform Component Object Model)

TODO
Example usage:
=============

//Picture Transfer Protocol (PTP) 
var ptp = Components.classes["@siragon.com/mtp/ptp;1"].getService();

//Mass Storage Class (MSC)
var msc = Components.classes["@siragon.com/mtp/msc;1"].getService();
