# API Design

## Base URL

/api/v1

---

## Upload File

POST /upload

Description:
Uploads a file to Amazon S3.

Response:

200 OK

{
  "message": "Upload successful"
}

---

## List Files

GET /files

Description:
Returns all uploaded files.

---

## Download File

GET /download/{filename}

Description:
Returns a pre-signed URL.

---

## Delete File

DELETE /delete/{filename}

Description:
Deletes the selected file.
