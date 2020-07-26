# Data partitioning and serving from multiple DCs
In the face of disaster, to avoid data loss and complete unserviceability, data is partitioned and served from different data centers.

# Introduction
During disaster, when all data resides in a single DC, there is a high chance of loosing all the data. Also, what if DB instance goes down, your service would be down. Whereas partitioning and serving the data from multiple DCs increases throughput. You can partition data based on geolocality of a user to a DC thereby reducing the latency. If disaster happens in a DC atleast your service will remain available for reads by serving from read replica present in the other DC. So this activity has myraid of benefits.

# Benefits
1. Disaster Recovery
1. Increased Availability
1. Reduced Latency as data is partitioned based on geolocation of the user

![Overview](/images/overview.jpg)
