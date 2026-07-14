# System Architecture

## High-Level Flow

User
│
▼
API Gateway
│
▼
Upload Lambda
│
▼
Amazon S3
│
▼
Metadata Lambda
│
▼
Amazon DynamoDB
│
▼
Download Lambda
│
▼
Pre-signed URL
│
▼
User

## Components

### API Gateway
Receives HTTP requests.

### Upload Lambda
Handles file uploads.

### Amazon S3
Stores uploaded files.

### Metadata Lambda
Stores file information.

### DynamoDB
Stores metadata.

### Download Lambda
Generates secure download URLs.
