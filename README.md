# Static-website-portfolio
This is a website I originally created using google sites. Exported the files and hosted it using AWS S3 buckets.
# My Static Website on AWS S3 ☁️

This is a simple static website hosted on **Amazon S3**.

## 🔗 Live Website

[Click here to view the site](http://myfirstportfoliohost.s3-website.eu-north-1.amazonaws.com))

📁 What's Inside
- HTML5 pages

🛠 How I Deployed this on AWS

1. Created an S3 bucket with public access.
2. Enabled static website hosting.
3. Uploaded my files.
4. Set bucket policy to allow public access.


🧑‍💻 Built  Whole Project With
- Google sites
- HTML
- AWS S3

Process/steps to completion:

-Exported google site to code.
-Set Up AWS aaccount
	-created an S3 bucket
	-Uploaded files into the bucket.
	Upon creation, there was a recommendation to experiment with AWS Amplify so I did. Changes will be made using Amplify as it showed promising features.
	-To make the website publicly accessible, I modify the permissions inn the bucket policy.
	-Copied the endpoint URL.
   Got hit with a 404 Not Found page.
	 Figured out the problem and it was a directory issue. On the 404 Not Found page, the error code: NoSuchKey Key:home.html were the pointers as to where I can start tackling the problem from.
  -Moved files to first access directory so I wouldn't have to the layered directory before the file can be accessed.(I don't know, I just understood how to solvve the problem.
	
	Website is now available and can be accessed using the endpoint URL.
	
