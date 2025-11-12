
#  Classic Load Balancer A Mini Project





## Introduction

 This project demonstrates how to deploy an Classic Load Balancer(CLB) in linux. The Classic Load Balancer it
 act like Round-Robin traffic distribution method. The classic load balancer is used in monolithic architecture
 website. The main objective of this project was to learn how to deploy classic load balancer. Finally, The CLB
 name of the classic load balancer is copied and tested to verify traffic disributtion

 ### Steps for Implement

 #### Step-1: Launch The Three Instance Server-1,Server-2,Server-3.

 * Click on the lauch instance.
 * Create a instances Server -3.

 [![Screenshot-2025-09-20-190221.png](https://i.postimg.cc/QMtv08g2/Screenshot-2025-09-20-190221.png)](https://postimg.cc/872yCV04)


 * Click on the advanced details.
 * Go to user data optionl.

 [![Screenshot-2025-09-20-191312.png](https://i.postimg.cc/qvf7PFDD/Screenshot-2025-09-20-191312.png)](https://postimg.cc/w7VHJwpD)


 *  Number of instance Three is creating the 3 instance.
* Click on the lanuch the instances.
* Edit the name of the server to server-1,server-2,server-3

[![Screenshot-2025-09-20-191510.png](https://i.postimg.cc/wB4MGjCL/Screenshot-2025-09-20-191510.png)](https://postimg.cc/TymTyfY3)

####  Step-2: Create the load balancer.

[![Screenshot-2025-09-20-191916.png](https://i.postimg.cc/Y2zKrsSy/Screenshot-2025-09-20-191916.png)](https://postimg.cc/Yj0y88Y1)

####  Step-3: Create the classic load balancer & create button.

[![Screenshot-2025-09-20-192020.png](https://i.postimg.cc/RF180Wvn/Screenshot-2025-09-20-192020.png)](https://postimg.cc/7G6XsYGx)

#### Step-4: Assign the name to the classic load balancer

[![Screenshot-2025-09-20-194108.png](https://i.postimg.cc/J4hJ7t8D/Screenshot-2025-09-20-194108.png)](https://postimg.cc/vDpD3Ycb)

####  Step-5: Right click on the availability zones & subnets & Select the security group.

[![Screenshot-2025-09-20-192246.png](https://i.postimg.cc/Fz6KHrb3/Screenshot-2025-09-20-192246.png)](https://postimg.cc/bSQP6jBw)

[![Screenshot-2025-09-20-192301.png](https://i.postimg.cc/ZKybLhFs/Screenshot-2025-09-20-192301.png)](https://postimg.cc/VdmPYphX)

####  Step-6: Add The Instances & Available Instances.

[![Screenshot-2025-09-20-192434.png](https://i.postimg.cc/vH91Znjm/Screenshot-2025-09-20-192434.png)](https://postimg.cc/5649PXfc)

####  Step-7: click on the create loadbalancer.

####  Step-8: Copy the DNS name of the CLB. 

[![Screenshot-2025-09-20-194227.png](https://i.postimg.cc/9Fzp8Lrn/Screenshot-2025-09-20-194227.png)](https://postimg.cc/mtfChN3Y)






##  Expected Output

*  Past CLB DNS name in the new incognito window.

####  Server-1 
[![Screenshot-2025-09-20-195342.png](https://i.postimg.cc/5jc6m9H1/Screenshot-2025-09-20-195342.png)](https://postimg.cc/zHjzzrSP)

#### Server-2
[![Screenshot-2025-09-20-195401.png](https://i.postimg.cc/NjDRQT9H/Screenshot-2025-09-20-195401.png)](https://postimg.cc/cvKvmvcx)

#### Server-3
[![Screenshot-2025-09-20-195415.png](https://i.postimg.cc/Qxr75Sc7/Screenshot-2025-09-20-195415.png)](https://postimg.cc/QV0VZQ4N)

## Summary

The Classic Load Balancer (CLB) is one of AWS’s legacy load balancing services. It operates at both Layer 4
 (TCP) and Layer 7 (HTTP/HTTPS), distributing incoming traffic across multiple EC2 instances to improve
 application availability and reliability. CLB supports basic features such as SSL termination and sticky sessions,
 making it suitable for small to medium-scale applications. However, for modern and advanced workloads,
 AWS recommends using Application Load Balancer (ALB) or Network Load Balancer (NLB)