This Python project utilizes boto3 to manipulate S3 buckets (an AWS service). Basically it:

1. Create 2 buckets
2. Create and upload files to buckets
3. Copy files into target buckets
4. Download files from buckets
5. Delete files from the buckets
6. Accesses changed from public and private to files
7. Encrypt files
8. Buckets versioning
9. Show Difference for buckets
10. Rollback one of the buckets
11. Print bucket names and their files
12. Delete all buckets

For this code to work we will need:
* Python 3
* AWS account
* Install requiremets.txt