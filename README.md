# Semester-3--Assignment-1

##Assignment for the week:
create a static website and host it on S3 bucket(private bucket) but with public read policy assigned, using cloud front for CDN.
To be submitted this week Saturday (11th May), latest 10am with screenshots of your Aws account bearing your name.
Input your steps and screenshots in your README file on GitHub.


##Steps

Create bucket and give it a unique name like "kunrad-too-like-wahala"

<img width="950" alt="Screen Shot 2024-05-10 at 8 31 41 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/90958b35-dd3a-40d4-8ac7-663ad8d1d2a0">


Upload your files and folders

<img width="950" alt="Screen Shot 2024-05-10 at 8 34 57 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/0d6c6ad8-c3dd-4970-84a4-f2c4a54cf09d">



Set up static website

<img width="950" alt="Screen Shot 2024-05-10 at 8 37 20 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/86641b31-ec36-47af-a7b3-1c744c7c7dc0">



<img width="950" alt="Screen Shot 2024-05-10 at 8 37 40 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/ef020895-e4b1-4946-bb37-38303ccce96a">



Create a CloudFront distribution and select your S3 bucket


<img width="950" alt="Screen Shot 2024-05-10 at 8 40 55 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/7c059445-d630-4e97-9b68-3d2df57512e5">




<img width="950" alt="Screen Shot 2024-05-10 at 9 14 18 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/6e4c4129-809e-4f23-bc1f-97b9c2226f61">



CLoudFront will generate a policy for you. Copy it and edit your s3 bucket policy


<img width="950" alt="Screen Shot 2024-05-10 at 9 17 33 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/5b3dfd59-2741-49dd-a650-c4c5622bb30b">


After editing your policy, wait for cloudfront to deploy and then use the provided url 
<img width="950" alt="Screen Shot 2024-05-10 at 9 18 09 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/99f37c51-a76c-4972-9549-f7acd95ccc25">


Your static site should come up

<img width="950" alt="Screen Shot 2024-05-10 at 9 18 27 PM" src="https://github.com/Uduakobong-Udombat/Semester-3--Assignment-1/assets/60650195/08a50471-7f0d-490e-a762-eac61af490b4">


That's all folks.


