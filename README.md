# AWS-Project-1
In this project I have forked the NETFLIX CLONE WEBSITE from @Bankole2000 which was available over open source at www://github.com.

NOTE: I can't provide the source link but have provided much of information about the project

<div align="center" style="text-align:center; margin:auto;">
<img align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/AWS_Simple_Icons_AWS_Cloud.svg/2560px-AWS_Simple_Icons_AWS_Cloud.svg.png" width="150"/>
</div>

<h3>Introduction</h3>
Here, I have made a project hosting a website using AWS EC2.

<h3>STEP 1</h3>
To host your Website on AWS EC2.

<h3>STEP 2</h3>
First zip the folder for the web files.

<h3>STEP 3</h3>
Next log into the management console and select S3 under service.

<h3>STEP 4</h3>
Create a bucket and upload that zip folder into that bucket.

<h3>STEP 5</h3>
Next, make that bucket and the object in the bucket public. 

<h3>STEP 6</h3>
Launch an EC2 instance with SSH access

<h3>STEP 7</h3>
Copy the instance’s public IP address and SSH into your EC2 instance 

<h3>STEP 8</h3>
Run the following commands in your terminal :
<ul>
<li> sudo su </li>
<li> yum update -y </li>
<li> yum install httpd -y </li>
<li> cd /var/www/html </li>
<li> wget s3_Object_URL </li>
<li> unzip name.zip </li>
<li> mv SubFolder_Name/* . </li>
<li> service httpd start  </li>
</ul>

<h3>STEP 9</h3>
Finally, copy public IP of your instance and paste it in the web browser.


<div align="center" style="text-align:center; margin:auto;">
<img align="center" src="https://media.licdn.com/dms/image/C5612AQG55BxdZ9xevw/article-cover_image-shrink_600_2000/0/1642961775042?e=2147483647&v=beta&t=7WlD3ldxsL35FfVsZ6TfqC8WSKZqhIss23u6Hm7fBgo" width="150"/>
</div>
