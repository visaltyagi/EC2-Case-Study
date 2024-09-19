# EC2-Case-Study
How to Replicate the Instance Into Other Region &amp; Take the EBS Volume Backup - EC2 Case Study

Problem Statement:

You work for XYZ Corporation. Your corporation is working on an application and they require secured web servers on Linux to launch the application.

You have been asked to:

1. Create an Instance in us-east-1 (N. Virginia) region with Linux OS and manage the requirement of web servers of your company using AMI

2. Replicate the instance in us-west-2 (Oregon) region

3. Build two EBS volumes and attach them to the instance in us-east-1 (N. Virginia) region

4. Delete one volume after detaching it and extend the size of other volume

5. Take backup of this EBS volume.


**Solution of This Assignment:**

**Step 1:** Create an EC2 instance in the "North Virginia" region & install the apache 2 on it.

**Step 2:** Create the AMI of this Instance.

**Step 3:** Using this AMI, create an EC2 instance in the "Oregon Region".

**Step 4:** Check the public IP Address of the "Oregon" region, you will notice that the same page will be shown here as the Northern Virginia here.

**Step 5:** Create the Two EBS Volumes in the Northern Virginia.

**Step 6:** Attach these volumes to the "EC2 Instance" present in the "Northern Virginia" region.

**Step 7:** Detach the Volume 2 from it & Delete this volume.

**Step 8:** Extend the Remaining EBS Volume Size.

**Step 9:** You will notice in your "Instances volume" section, your volume is successfully modified.

**Step 10:** Take the backup of this EBS Volume.

**For more detailed solution, checkout this link:** https://medium.com/devops-guides/how-to-replicate-the-instance-into-other-region-take-the-ebs-volume-backup-ec2-case-study-32a0b0db1da4 
