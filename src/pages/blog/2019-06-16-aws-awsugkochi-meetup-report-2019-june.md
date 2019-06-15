---
templateKey: blog-post
title: Meetup Report - June 2019 - AWS EC2 Spot Instances - Save 90% on your EC2 costs
date: 2019-06-15T10:00:10.000Z
description: Meetup Report - June 2019 - AWS EC2 Spot Instances - Save 90% on your EC2 costs
tags:
  - aws
  - awsugkochi
  - meetup
  - ec2
  - amazon
  - usergroups
  - spotinstances
  - ec2spot
  - eks
  - ecs
  - autoscaling
---

This event was organized by [Amazon User Group Kochi](https://awsugkochi.in) in association with EC2 Spot Team at Amazon Web Services and [IBS Software Services](https://www.ibsplc.com/).

<br>

![junemeetupa01](/img/awsugkochi-meetup-june-2019-01.png)

<br> 

This time our topic was `AWS EC2 Spot Instances - Save 90% on your EC2 costs` and the session was taken by [Chakravarthy Nagarajan](https://www.linkedin.com/in/chakravarthy-nagarajan-7653311a/), Solution Architect - EC2 Spot Specialist at Amazon Internet Services Private Limited (AWS)


Amazon EC2 Spot instances offer spare compute capacity availavle in the AWS cloud at steep discounts compared to On-Demand instances. Spot instances enable you to optimize your costs on the AWS cloud and scale your application's throughput up to 10X for the same budget. 


<br>

![junemeetupa02](/img/awsugkochi-meetup-june-2019-02.png)

<br> 


Meetup Session started with a self-introduction by all attendees. Then, [Sridhar Bharadwaj](https://www.linkedin.com/in/sridhar-bharadwaj), Business Development Manager - EC2 Spot at Amazon Web Services (AWS) introduced our speaker of the day [Chakravarthy Nagarajan](https://www.linkedin.com/in/chakravarthy-nagarajan-7653311a/).

<br> 

![junemeetupa03](/img/awsugkochi-meetup-june-2019-03.png)

<br> 

Chakra walked us through 

-   EC2 Spot - Basics
-   EC2 Spot – Pricing model
-   EC2 Spot ready Workloads and AWS Managed Services
-   EC2 Spot Diversification Best Practices
-   Handling Spot Instance Interruptions
-   EC2 Spot Orchestration options - Spotfleet & Auto Scaling Groups (ASG) with EC2 Fleet
-   Demo - Spotfleet and ASG
-   Deploying specific Workloads on EC2 Spot instances (eg. Containers, Data Anaytics, ML, Web Services, etc)

<br> 

<br> 

![junemeetupa04](/img/awsugkochi-meetup-june-2019-04.png)

<br>


## Notes 


#### Spot Instances

Amazon EC2 Spot Instances let you take advantage of unused EC2 capacity in the AWS cloud. Spot Instances are available at up to a 90% discount compared to On-Demand prices. You can use Spot Instances for various stateless, fault-tolerant, or flexible applications such as big data, containerized workloads, CI/CD, web servers, high-performance computing (HPC), and other test & development workloads.


#### Spot Instances - Pricing

With Spot instances, You pay the Spot price that's in effect for the time period your instances are running. Spot instance prices are set by Amazon EC2 and adjust gradually based on long-term trends in supply and demand for Spot instance capacity.

Spot instances are available at a discount of up to 90% off compared to On-Demand pricing. To compare the current Spot prices against standard On-Demand rates, visit the Spot Instance Advisor.

#### Best Practices

*Spot Rules*

Learn two simple rules to follow to maximize compute cost savings

  1. Spot Capacity Pools have separate prices and change infrequently
  2. Amazon EC2 will give you a 2 minute warning when we need the capacity back

*Instance Flexibility*

Test your application on different instance types when possible. Because prices fluctuate independently for each instance type in an Availability Zone, you can often get more compute capacity for the same price when you have instance type flexibility

*Fleet API*

EC2 Fleet simplifies the provisioning of EC2 capacity across different instance types, AZs, and across On-Demand, RIs and Spot purchase models. The same functionality is available in Spot Fleet.

#### Handling interruptions

Spot Instances receive a two-minute notice when these instances are about to be reclaimed by EC2, because EC2 needs the capacity back. Use Cloudwatch Events to get notfification when the Spot instances are interrupted by Amazon EC2. Also review the Spot Instance Advisor for average frequency of interruption for different Spot Pools.

<br>

## Tools / Resources

1. **Spot Instance Advisor** : https://aws.amazon.com/ec2/spot/instance-advisor/

2. **EC2 Spot Workshop** : https://ec2spotworkshops.com

<br>

## Additional referrences


1. **CI/CD Workloads on Spot Instances**  : [Watch Video](https://youtu.be/8gGItacZjps)

2. **Containerized Workloads with Spot Instances**  : [Watch Video](https://youtu.be/H1TJKamaakc)

3. **Big Data Workloads on Spot Instances** : [Watch Video](https://youtu.be/FyY_Lyc5Ddg)

4. **Rendering Workloads on Spot Instances** : [Watch Video](https://youtu.be/kfxrsedi4kM)

5. **Web Applications and Services on Spot Instances** : [Watch Video](https://youtu.be/rlYLbs33Ofs)

6. **Amazon Online Tech Talks** : [Watch Video](https://youtu.be/O4uw7eIVrZs)


<br>

<br>

The event concluded by a Thank You note by [Abhilash Nair](https://www.linkedin.com/in/hiabhilash/).



Once again on behalft of AWS User Group Kochi. We would like to thank,


1. [Sridhar Bharadwaj](https://www.linkedin.com/in/sridhar-bharadwaj) and [Chakravarthy Nagarajan](https://www.linkedin.com/in/chakravarthy-nagarajan-7653311a/) for coming down to Kochi and sharing knowledge to our community members.

2. [IBS Software Services](https://www.ibsplc.com/) for providing venue and refreshments.

<br>


<br> <br>

# AWS Comunity Day Annoucements

1. [Ahmedabad 26th June 2019](https://awsahmedabad.community)
2. [Bangalore 26th & 27th July 2019](https://communityday.awsugblr.in)
3. [Chennai 10th August 2019](https://communityday.awsugchn.in)


<br> <br>
## Join the community

Join the AWSUGKOCHI community - you can find us on our [About](https://awsugkochi.in/about) page

<br> 

Help us to grow this community, please share this page to your colleagues and friends - Thank you.
