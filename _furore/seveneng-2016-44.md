---
uid: seveneng
date: 2016-10-24
enddate: 2016-10-30
week: 44
generator: furore
---

1. Measure the performance of PIH-gatekeeper(infrastructure within UCN), mainly the operation latency when serving clients' requests. As there are different branches based on the validity of client certificate and/or the right to access a data holding unikernel, accordingly there are different scenarios where the PIH-gatekeeper need to be measured against.

2. As mort successfully updated the dom0 OS from Debian-based to Alpine earlier last week, I started to port the system to the new platform. The out-of-box SDcard image has insufficient storage space assigned for dom0, I can't install required tools/libraries in it, then I started to rebuild one image which has larger persistent storage space.

