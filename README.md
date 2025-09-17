# Apache-TomcatSQL-Project

Multi-Tier Web Application Infrastructure Project
This project demonstrates a complete multi-tier web application stack deployed using both automated and manual approaches. The architecture consists of:

**Services Used:**

1. Web Server: Nginx (Load Balancer/Reverse Proxy)
2. Application Server: Apache Tomcat with Java application
3. Database: MariaDB/MySQL
4. Caching: Memcached
5. Message Queue: RabbitMQ
6. Build Tool: Apache Maven

**Architecture:**
1. Web Tier: Nginx reverse proxy routing traffic to Tomcat
2. Application Tier: Java web application (vProfile) running on Tomcat
3. Database Tier: MariaDB with pre-loaded application data
4. Caching Layer: Memcached for performance optimization
5. Message Broker: RabbitMQ for asynchronous communication
6. Opensearch : Indexing/Search service

**Deployment Approaches:**
**Automated Deployment:**

1. Uses Vagrant for infrastructure provisioning
2. Automated VM creation with predefined configurations
3. Shell script provisioning for each service component
4. Multi-OS support (CentOS Stream 9, Ubuntu)

**Manual Deployment:**

1. Individual shell scripts for each service setup
2. Manual configuration and deployment steps
3. Cross-platform compatibility scripts

**Key Features:**

1. Infrastructure as Code using Vagrant
2. Multi-OS compatibility (CentOS/RHEL and Ubuntu/Debian)
3. Automated service configuration and startup
4. Database initialization with application schema
5. Load balancing and reverse proxy setup
6. Firewall configuration for security
7. Service orchestration across multiple VMs

This project showcases modern DevOps practices including automation, infrastructure as code, and multi-tier application deployment strategies.


