---
title: Home
nav_order: 1
---

# UCSMA Docs
This site contains documentations for all UCSMA projects. The content in this page intends to provide a short overview of each projects, while the details can be found in the subpages in the navigation sidebar. 

## Rate control
The rate control protocol is the key part of the ultimate goal of UCSMA, which attempts to maintain fairness among different nodes in an ad-hoc wireless network. There are two parts of the rate control protocol:

1. buffer enqueue delay: a packet will need to wait a certain time interval (positively proportional to the current buffer size) before being enqueued into the transmission buffer; 
2. contention window adjustment: we set lower CW for nodes with fuller buffer to allow their packets to be send our quicker.
