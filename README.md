# 3-Tier-WebApp-Security-and-Connectivity
Understanding AWS Route 53 DNS Resolver, WAF Firewall, ACM, ALB, EC2 web servere

### AWS Route 53 - connects user requests to applications, resolves domain names, and returns IP addresses

### Create a hosted zone for the domain

### Create an alias record to connect the domain to an ALB

### AWS WAF provides protection against attacks at the application layer (OSI Layer 7) as against NACLs/Security Groups which provide protection at the network/transport layer (OSI Layer 3/4)

### WAF components: 

### AWS ACM - Provisions, manages, and deploys public/private SSL/TLS Certificates
Request a public certificate

### AWS ALB - Distributes incoming traffic across multiple targets, such as EC2 instances.

### Create an application load balancer

### Create a target group that should consist of the EC2 webservers, so the ALB can route traffic to them.
