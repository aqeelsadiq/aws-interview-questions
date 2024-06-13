### 1. What is an Elastic Load Balancer (ELB)?
An Elastic Load Balancer (ELB) is a managed AWS service that automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, or IP addresses, to ensure high availability and fault tolerance.
### 2. What are the three types of Elastic Load Balancers available in AWS?
There are three types of Elastic Load Balancers: Application Load Balancer (ALB), Network Load Balancer (NLB), and Gateway Load Balancer (GWLB).
### 3. What is the main difference between Application Load Balancer (ALB) and Network Load Balancer (NLB)?
ALB operates at the application layer and supports advanced routing, including content-based routing and path-based routing. NLB operates at the transport layer and provides ultra-low latency and high throughput.

### 4. What are some key features of Application Load Balancer (ALB)?
ALB supports features like dynamic port mapping, path-based routing, support for HTTP/2 and WebSocket protocols, and content-based routing using listeners and rules.

### 5. When should you use Network Load Balancer (NLB)?
NLB is suitable for scenarios that require extreme performance, high throughput, and low latency, such as gaming applications and real-time streaming.

### 6. What is a target group in Elastic Load Balancing?
A target group is a logical grouping of targets (such as EC2 instances) registered with a load balancer. ALB and NLB use target groups to route requests to registered targets.