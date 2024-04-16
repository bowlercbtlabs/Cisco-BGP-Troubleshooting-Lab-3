# Cisco BGP Troubleshooting - Lab 3

## Trouble Ticket #1

Problem
- You have recently upgraded your network to a Dual Homed BGP configuration for redundancy and to a higher speed T3 Internet connection (45MB). Your network administrator has brought to your attention that during peak business hours your customers are experiencing latency. After further investigation you find that to get to networks behind the ISP the traffic is flowing over the backup T1 (1.5MB) link.

Desired outcome
- Configure the network so that the Primary T3 (45MB) link is used to route all traffic out to the ISP. Do not configure a Cisco Proprietary BGP attribute to complete this task
- Do not remove any configuration on either router to restore connectivity.  

## Trouble Ticket #2

### Problem
- After you have restored the above task, your network administrator has brought to your attention that return traffic from the ISP to your network is still taking the backup T1 (1.5MB) link. 

### Desired outcome
- Configure the network so that all the ISP traffic coming into your network is routed over the Primary T3 (45MB) link. Do not use MED to complete this task.

