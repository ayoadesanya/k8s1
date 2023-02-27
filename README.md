# k8s1
k8s1
Deploy 2 containers each with it’s own database
Schedule scale-out of the ASG between 8:00 AM and 6:00 PM
Container 1 runs code that returns users from a database
Container 2 runs code that returns shifts from a database
Ensure scale out when CPU utilization is 70%
Configure rolling deployments and rollbacks
Attach a policy with a condition to restrict members of a specific group from running specific commands
Create a CloudFormation stack of the configuration for deployment to Development and Production
Create a Route53 latency based policy that tracks an alarm for triggering scale-out

