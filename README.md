# ofbiz-usps
Disentanglement of the 3rd party Shipment Integration Solution for USPS in the OFBiz Product/Facility application into a separate, hot-deploy component

##Development
Just put the following in the svn:externals properties of the hot-deploy folder of your OFBiz implementation for a checkout:

usps         https://github.com/ORRTIZ/ofbiz-usps/trunk

After having updated the hot-deploy folder (to execute the checkout from the repository), you'll need to build OFBiz again (./ant build) and load the seed, seed-initial and  - optionally- demo datasets.

