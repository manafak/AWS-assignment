 Deploying a static website with AWS S3 using ClouFront as the CDN
 
 STEPS:
 I logged into my AWS account as the root user.
 I creasted a s3 bucket named "kahmanny-assignment-aws"

 <img width="1680" alt="Screenshot 2024-05-10 at 11 34 05" src="https://github.com/manafak/AWS-assignment/assets/149635098/c639f398-3b08-4245-9689-d40bc9000f5e">

<img width="1680" alt="Screenshot 2024-05-10 at 11 34 39" src="https://github.com/manafak/AWS-assignment/assets/149635098/99f45708-7183-45ae-b1e6-d6e487919c12">

Upload Ststic Website files to S3 Bucket

<img width="1680" alt="Screenshot 2024-05-10 at 11 34 48" src="https://github.com/manafak/AWS-assignment/assets/149635098/e60cc180-70b4-4632-9707-3fc6f172aad9">


Next, we enable Static Website Hosting on S3 bucket,from the Properties tab we look for Static website hosting section and click on the Edit button.

Select Enable option for Static website hosting. Select Host a static website.
Enter the Index document file name (index.html) that will serve as the home page for your static website.

Add a Bucket Policy

<img width="1680" alt="Screenshot 2024-05-10 at 11 35 03" src="https://github.com/manafak/AWS-assignment/assets/149635098/3e28f4b4-cda3-4fca-b3e8-8eaedaeba125">

Save it and find the URL under Bucket website endpoint.

<img width="1680" alt="Screenshot 2024-05-10 at 11 35 14" src="https://github.com/manafak/AWS-assignment/assets/149635098/43fc2d2d-5f82-4d37-b235-a45a53788b28">

<img width="1680" alt="Screenshot 2024-05-10 at 11 35 27" src="https://github.com/manafak/AWS-assignment/assets/149635098/99d1dbb9-dc74-464c-be74-ef9726976d85">

Configuring the CloudFront Distribution:

I created and configured a CloudFront distribution using the static S3 end-point URL
