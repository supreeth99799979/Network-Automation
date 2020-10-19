---
__Description__

- To implement a simple web service in which we deploy a simple PHP script on webservers running Nginx along with HAProxy load balancer using Ansible tool.

- The page which is being maintained renders the hostname, IP, and port of the server running it. 

---

__HAProxy__

HAProxy (High Availability Proxy) is used by RightScale for load balancing in the cloud.
Here to run multiple web servers we need three Nginx servers running on three different platforms. Hence HAproxy is deployed to load balance between three servers. 



__Bastion Host__

Bastion host also known as a jump server which is used to manage access to a private network from an external network.


---

__To do__

- Write an ansible-playbook, site.yaml, that deploys the HAproxy, and Nginx on appropriate existing hosts.



- To run the playbook use the command:ansible-playbook -i hosts site.yaml



