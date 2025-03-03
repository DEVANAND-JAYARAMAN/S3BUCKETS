📌 Steps Covered:
✅ Step 1: Log in to AWS Management Console
✅ Step 2: Create an S3 Bucket
✅ Step 3: Upload Website Files (index.html and other assets)
✅ Step 4: Configure Static Website Hosting
✅ Step 5: Make Files Public (Set Permissions)
✅ Step 6: Access Your Website via S3 URL
✅ Step 7: (Optional) Enable Custom Domain Using Route 53 & CloudFront
✅ Step 8: Delete the S3 Bucket to Prevent Costs

📝 Detailed Steps
Step 1: Log in to AWS Management Console
Open AWS Management Console.
Search for "S3" in the AWS search bar and open the S3 service.
Step 2: Create an S3 Bucket
Click Create bucket.
Enter a unique bucket name (e.g., my-website-bucket).
Choose a region closest to your audience.
Uncheck "Block all public access" (for public hosting).
Click Create bucket.
Step 3: Upload Website Files
Open your bucket and click Upload.
Add index.html, CSS, JavaScript, and other assets.
Click Upload.
Step 4: Configure Static Website Hosting
Go to the Properties tab.
Scroll down to Static website hosting and click Edit.
Select Enable and choose Host a static website.
Set index.html as the default document.
Click Save changes.
Step 5: Make Files Public
Adjust bucket permissions to allow public access.
Apply a Bucket Policy to grant read access.
Step 6: Access Your Website
Go to the Properties tab.
Copy the Endpoint URL 
Open it in a browser to see your hosted website.
Step 7: Delete the S3 Bucket to Avoid Costs
💰 To prevent unnecessary AWS charges, delete the S3 bucket after testing:

Go to Amazon S3 in the AWS Console.
Select your bucket.
Click Empty bucket to delete all files.
Click Delete bucket and confirm.
🚀 Now, your website is hosted successfully, and you've learned how to delete it to avoid extra costs!
