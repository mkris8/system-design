Scalability
====
As a system grows, the performance starts to degrade unless we adapt it to deal with that growth.

Scalability is the property of a system to handle a growing amount of load by adding resources to the system.
### How can a System Grow?
A system can grow in several dimensions.

<img src="https://github.com/user-attachments/assets/83d7352b-772c-4e26-8e34-a98277b6bec7" alt="Image" width="300">

##How to Scale a System?
Here are 10 common ways to make a system scalable:
## 1. Vertical Scaling (Scale up)
This means adding more power to your existing machines by upgrading server with more RAM, faster CPUs, or additional storage. It's a good approach for simpler architectures but has limitations in how far you can go.
<img src="https://github.com/user-attachments/assets/47802a2f-bec0-4ab6-b796-c6ade811b6e7" alt="Image" width="300">

## 2. Horizontal Scaling (Scale out)
This means adding more machines to your system to spread the workload across multiple servers. It's often considered the most effective way to scale for large systems.
Example: Netflix uses horizontal scaling for its streaming service, adding more servers to their clusters to handle the growing number of users and data traffic.

<img src="https://github.com/user-attachments/assets/b12f45f7-c1d8-4abd-8e68-043790a4c900" alt="Image" width="300">

## 3. Load Balancing
Load balancing is the process of distributing traffic across multiple servers to ensure no single server becomes overwhelmed.
https://github.com/mkris8/system-design/blob/main/load-balancing.md

## 4. Caching
Store frequently accessed data in-memory (like RAM) to reduce the load on the server or database. Implement caching can dramatically improve response times.

## 5. Content Delivery Networks (CDNs)
Distribute static assets (images, videos, etc.) closer to users. This can reduce latency and result in faster load times.

## 6. Partitioning
Split data or functionality across multiple nodes/servers to distribute workload and avoid bottlenecks.

## 7. Asynchronous communication
Defer long-running or non-critical tasks to background queues or message brokers. This ensures your main application remains responsive to users.

## 8. Microservices Architecture
Break down your application into smaller, independent services that can be scaled independently. This improves resilience and allows teams to work on specific components in parallel.

## 9. Auto-Scaling
Automatically adjust the number of active servers based on the current load. This ensures that the system can handle spikes in traffic without manual intervention.

## 10. Multi-region Deployment
Deploy the application in multiple data centers or cloud regions to reduce latency and improve redundancy.








