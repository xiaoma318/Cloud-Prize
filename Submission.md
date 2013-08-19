Actually, I have three submission, ASG Console, myEdda and myJanitor

## Which Categories Best Fit Your Submission and Why?

1. The ASG Console: Best Contribution to Operational Tools, Availability, and Manageability  
   Since it provides a user friendly conolse for AutoScaling Service, which AWS don't offer, and also you can remotely
   Control your instances other than using some remote control tool, and what makes it more convenient is you can do 
   this to multiple instances at the same time.

2. myEdda & myJanitor: Best usability enhancement
   The original Edda and Simian Army(Janitor Monkey) don't provide any interface, you need to enter every command in order to keep track of your resource. myEdda and myJanitor provides a web interface for this, which makes it more convenient for using. Users don't need to do the build and run process, all they need to do is put them on some server container(like Apache Tomcat) and run them, which greatly simplify the using process.


## Describe your Submission
Team name: ForDream<br>
Team members : Cheng(leader,github id:xiaoma318) and Joe(github id:joehack3r)

1. ASGConsole provides a user friendly manage console for the AWS AutoScaling Service, which AWS don't have currently.
Basic function includes Display/Create/Delete/Edit Launch Configuration Group, AutoScaling Group and Scaling Policy 
Group. Advanced funciton is you can remotely enter command to the instances in AutoScaling Group, and it support to do 
this to multiple instances at the same time. 

2. myEdda is a webapp that allows users to review their AWS resource, which is based on the Netfliex Edda. Information includes EC2 Instance, S3 Buckets, AutoScaling Groups and Security Groups, users can not only keep track of the current information, but can also review the past records. And for instance, it provides advanced search and filter function, allowing users to search their instances using AMI, IP address, tags, etc.

3. myJanitor is a GUI for Netflix Janitor Monkey, which is a part of their Simian Army application. It can keep track of your unused AWS resources and help you to terminate them. The basic process is "Mark, Notify, Delete", first it goes throught all your aws resrouce, finds some unused resources under the rule you specified and marks them, then send you notifications if it deciedes to delete that marked resource, after some time, the resource will be deleted automatically. Also, you can unmarked the resouce to make it not be deleted yourself.
   

## Provide Links to Github Repo's for your Submission
1. ASG Console: https://github.com/xiaoma318/ASGConsole.git
2. myEdda: https://github.com/xiaoma318/myEdda.git
3. myJanitor:https://github.com/xiaoma318/myJanitor.git
