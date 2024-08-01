Load Balancing (LB)
====

Help scale horizontally across an ever-increasing number of servers.

<img src="https://github.com/user-attachments/assets/cbdf2133-bde4-4544-809e-676ddfb1e0a1" alt="Image" width="300">

## LB locations
- Between user and web server
- Between web servers and an internal platform layer (application servers, cache servers)
- Between internal platform layer and database

## Algorithms
- Least connection
- Least response time
- Least bandwidth
- Round robin
- Weighted round robin
- IP hash

## Implementation
- Hardware load balancers (f5)
- Software load balancers (Nginx, HAProxy, Apache HTTP Server (with mod_proxy_balancer))
