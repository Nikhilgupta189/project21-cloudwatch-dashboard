# Project 21: CloudWatch Monitoring Dashboard

## Objective
Create an AWS CloudWatch dashboard to visualize EC2 and Application Load Balancer performance.

## Technologies Used
- Amazon CloudWatch
- Amazon EC2
- AWS Application Load Balancer
- AWS Target Groups

## Implementation
1. Reused two EC2 instances from Project 20.
2. Created the CloudWatch dashboard `project21-monitoring-dashboard`.
3. Added CPUUtilization metrics for both EC2 instances.
4. Added the ALB RequestCount metric.
5. Added the HealthyHostCount metric.
6. Verified that CloudWatch displayed performance data.
7. Captured a dashboard screenshot.

## Results
- Both EC2 instances displayed CPU utilization metrics.
- The ALB RequestCount graph showed incoming requests.
- HealthyHostCount displayed 2 healthy backend targets.
- All three monitoring graphs were visible on the dashboard.

## Conclusion
Successfully configured a centralized AWS CloudWatch monitoring dashboard to visualize infrastructure performance and load balancer health.
