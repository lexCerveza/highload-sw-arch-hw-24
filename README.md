# highload-sw-arch-hw-24

## 1. Set up 2 EC2 instances
![alt text](./images/ec2-instances.png)

## 2. Set up inbound rule for HTTP 80 port
![alt text](./images/inbound-rule-instance.png)

## 3. Launched python server on port 80 on 1 instance
![alt text](./images/ec2-healthcheck.png)

## 4. Created load balancer with 2 assigned instances and checked that 1 instance is down and 1 is up
![alt text](./images/load-balancer.png)
