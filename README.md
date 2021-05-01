# Bucket Uploader

Test to see if an S3 bucket is misconfigured to allow public uploading of files

## Requirements

- AWS CLI set up and configured
- Wordlist of bucket names
- File to upload

# Usage

cat bucket-name-wordlist.txt | ./bucketUploader test-file
