# DeployAutoScalingGroup

This script redeploys all instances in an Auto Scaling Group, with an Elastic Load Balancer, while maintaining the same number of healthy instances and with zero downtime. 

For an in-depth explanation of how the script works, as well as it's prerequisites, you can [read more here](http://kylewbanks.com/blog/Redeploying-an-Application-in-an-AWS-Auto-Scaling-Group-Behind-an-ELB-with-Zero-Downtime).

# Contributing

The script has worked wonders for one project, but can likely be improved upon to make it a more generally useful. Specifically, I'd like to remove the need for a special Scaling Policy and Termination Policy. If you'd like to solve either of these two issues, or have any other ideas to improve upon the script, please feel free to submit a pull-request.
