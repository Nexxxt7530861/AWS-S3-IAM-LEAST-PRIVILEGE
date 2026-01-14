# AWS S3 IAM Least Privilege

## Overview
This project demonstrates the principle of least privilege by granting an IAM user only the minimum permissions required to access an Amazon S3 bucket.

## Architecture
- Private S3 bucket with public access blocked
- IAM user with no default permissions
- Custom IAM policy allowing:
  - List bucket contents
  - Read and upload objects
  - Denial of delete and administrative actions

## Security Focus
The IAM policy ensures the user cannot delete objects, modify bucket policies, or perform destructive actions, reducing security risk.

## Skills Demonstrated
- AWS IAM policy design
- S3 access control
- Security best practices
- AWS Console and CLI usage

## Screenshots
Screenshots documenting each step are included in the `screenshots/` directory.

## Notes
This project was built entirely within the AWS Free Tier.
