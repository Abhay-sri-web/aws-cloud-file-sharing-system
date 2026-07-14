# AWS Infrastructure

## Region

ap-south-1 (Mumbai)

## S3 Buckets

- cloud-file-sharing-upload
- cloud-file-sharing-download

## DynamoDB

Table Name:
FileMetadata

Partition Key:
fileId (String)

## Lambda Functions

- upload_lambda
- metadata_lambda
- download_lambda

## API Gateway

Base Path:
/api/v1

Endpoints

POST /upload

GET /files

GET /download/{id}

DELETE /delete/{id}

## IAM

Execution Role

CloudFileSharingRole
