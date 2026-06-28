# Cloud Storage Explorer using Amazon S3

## Project Overview

This project demonstrates the basic operations of Amazon S3 (Simple Storage Service) using the AWS Management Console. The objective is to understand cloud object storage, bucket management, object operations, versioning, storage classes, and secure access.

---

## Project Objectives

- Create an Amazon S3 bucket
- Upload files and folders
- Organize objects inside folders
- Download stored objects
- Enable bucket versioning
- Modify object storage class
- Generate object URL
- Understand secure object access
- Delete objects from bucket

---

## AWS Services Used

- Amazon S3
- AWS Management Console

---

## Region

US East (N. Virginia)
```

---

## Bucket Details

```
Bucket Name:
shivam-cloud-storage

Region:
us-east-1

Storage Type:
Amazon S3 Standard Bucket
```

---

## Files Used

```
index.html
style.css
main.js

Folder:
documents/
```

---

## Tasks Performed

### Step 1 – Created S3 Bucket

- Created a new S3 bucket
- Selected US East (N. Virginia)
- Bucket created successfully

---

### Step 2 – Uploaded Files

Uploaded

- index.html
- style.css
- main.js

---

### Step 3 – Created Folder

Created folder

documents/

---

### Step 4 – Uploaded Files into Folder

Uploaded HTML, CSS and JavaScript files inside the documents folder.

---

### Step 5 – Downloaded Object

Downloaded

index.html

to verify successful storage.

---

### Step 6 – Enabled Bucket Versioning

Bucket Versioning was enabled successfully.

Benefits

- Protects against accidental deletion
- Maintains object history
- Allows recovery of previous versions

---

### Step 7 – Changed Storage Class

Storage Class changed from

Standard

to

Standard-IA

Benefits

- Lower storage cost
- Suitable for infrequently accessed files

---

### Step 8 – Viewed Object Properties

Verified

- Object Name
- Object Size
- Last Modified
- Storage Class
- Object URL
- ETag
- ARN

---

### Step 9 – Generated Object URL

Generated Object URL for

documents/index.html

When opened in browser

Access Denied

Reason

Bucket is private.

This demonstrates secure access control in Amazon S3.

---

### Step 10 – Deleted Objects

Successfully deleted uploaded objects.

Deletion completed without errors.

---

## Security Observation

The generated Object URL returned

Access Denied

because

- Block Public Access is enabled
- Bucket policy does not allow anonymous users
- Objects are private by default

This confirms secure bucket configuration.

---

## Learning Outcomes

- Amazon S3 Bucket Management
- Object Upload and Download
- Folder Organization
- Bucket Versioning
- Storage Classes
- Object Properties
- Secure Access
- Object URL
- Object Deletion

---

## Folder Structure

```
Cloud-Storage-Explorer/

│
├── README.md
├── Architecture.png
├── commands.md
└── screenshots/
      ├── 01-create-bucket.png
      ├── 02-upload-files.png
      ├── 03-folder-created.png
      ├── 04-upload-folder-files.png
      ├── 05-download-object.png
      ├── 06-versioning.png
      ├── 07-storage-class.png
      ├── 08-object-properties.png
      ├── 09-object-url.png
      ├── 10-access-denied.png
      └── 11-delete-object.png
```

---

## Conclusion

This project successfully demonstrates the core functionality of Amazon S3, including bucket creation, object management, versioning, storage optimization, secure object access, and object deletion. It provides hands-on experience with AWS cloud storage services and best practices for secure object storage.
