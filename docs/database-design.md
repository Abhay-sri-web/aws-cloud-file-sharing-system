# DynamoDB Design

Table Name

FileMetadata

Partition Key

fileId (String)

Attributes

- fileName
- fileSize
- uploadDate
- fileType
- uploadedBy
- s3Key

Example Item

{
  "fileId":"12345",
  "fileName":"image.jpg",
  "fileSize":"250KB",
  "fileType":"image/jpeg",
  "uploadDate":"2026-07-14",
  "s3Key":"uploads/image.jpg"
}
