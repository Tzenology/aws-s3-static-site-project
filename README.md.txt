# AWS S3 Static Website Project

This is a beginner cloud project where I hosted a static website using Amazon S3.

## 🌐 Project Goal
To learn how to host a static website on AWS S3, configure permissions, and troubleshoot access issues like 403 errors.

## 🧰 Tools & Technologies
- Amazon S3
- ACLs and Bucket Policies
- HTML/CSS
- Static Website Hosting (AWS Console)

## 📸 Screenshots

1. **S3 Bucket Creation**
![Bucket Created](https://github.com/Tzenology/aws-s3-static-site-project/blob/main/screenshots/create-bucket.png?raw=true) 

2. **File Upload** 
![Upload Files](./screenshots/file-upload.png) 

3. **403 Forbidden Error** 
![403 Error](./screenshots/error-403-forbidden.png)

4. **Permission Settings** 
![Set Permissions](./screenshots/setup-permission.png)

5. **Website Successfully Hosted** 
![Live Site](./screenshots/website-live.png)


## ✅ Steps Taken
1. Created an S3 bucket and chose Cape Town as the region
2. Disabled “Block all public access” and enabled static website hosting
3. Uploaded `index.html` and asset files
4. Encountered 403 error – fixed it by making files public using ACLs
5. Viewed my website live using the S3 bucket endpoint

## 💭 Reflections
- Most rewarding part: seeing my live website online!
- Learned how access settings work in AWS and how to troubleshoot permissions

## 🔜 Next Steps
- Try automating this setup with Terraform
- Explore CloudFront for better delivery and security


