# 📄 Static Help Page Using Amazon S3 + CloudFront

A beginner-friendly AWS mini project where I hosted a static FAQ (Help Center) page using **Amazon S3** for storage and **CloudFront** for fast global delivery.

---

## 🌐 Live Demo  
🔗 d3q8yzuan8w4xc.cloudfront.net

---

## ✅ Tech Stack
- **Amazon S3** – static website hosting  
- **Amazon CloudFront** – CDN for speed and reliability  
- **HTML + CSS** – lightweight front-end  
- **S3 Bucket Policy** – public access configuration  
- **(Optional)** Route 53 – for a custom domain name

---

## 🛠️ Project Summary

I hosted a simple Help Center page (`faq.html`) entirely using AWS infrastructure, and globally distributed via CloudFront.

---

## 🚀 How I Built It

### 1. Write the Page
Created a basic FAQ-style HTML page styled with CSS (ChatGPT-assisted).

### 2. Upload to S3
- Created a new bucket and uploaded `faq.html`
- Disabled “Block all public access”
- Enabled **Static website hosting** and set `faq.html` as the index document

### 3. Set Public Access
- Added a **bucket policy** to allow `s3:GetObject` for public read access

### 4. Connect CloudFront
- Created a CloudFront distribution
- Set the S3 static website URL as origin
- Copied the CloudFront domain URL after deployment

### 5. (Optional) Add Custom Domain via Route 53
- You may use **Route 53** to map a domain like `help.mysite.com`


---

## 📘 What I Learned

- How to host static sites with **Amazon S3**
- Use of **CloudFront** to improve speed and availability
- Managing **bucket policies** securely
- Deploying static pages using only AWS-native tools







