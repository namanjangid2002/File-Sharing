# File Sharing

---

File Sharing is a web application that allows users to upload files and generate a shareable link for accessing the file. Additionally, users can send an email directly from the application containing the link to the uploaded file.
It is built using Node.js, Express.js and Mongo DB.

---

## Features

- Upload files and generate shareable links.

- Send an email with the file link directly from the application.

- Simple and user-friendly interface.
---

## Run Locally

Clone the project

```bash
  git clone https://github.com/namanjangid2002/File-Sharing.git
```

Go to the project directory

```bash
  cd File-Sharing
```

Install dependencies

```bash
  npm i
```

#### Environment Variables

To run this project, you will need to add the following environment variables to your .env file in the server directory

`MONGO_URI`: `YOUR MONGO DATABASE_URL`

`BASE_URL`:`YOUR PROJECT BASE_URL`

`SMTP_HOST`:`your_email_service_provider_host`

`SMTP_PORT`:`your_email_service_provider_port`

`MAIL_USER`:`your_email_address`

`MAIL_PASS`:`your_email_password`

Run the Application

```bash
  npm start
```

Open your web browser and visit http://localhost:3000 to access File-Sharing.

---

## Usage (Testing)

1. **Upload a File:** Navigate to http://localhost:3000 and use the file upload interface to upload a file.
2. **Generate Shareable Link:** After the file is uploaded, a shareable link will be generated.

4. **Send Email:** Enter the recipient's email address and click on the send button to email the link.
## Screenshots

#### Upload Screen

![upload_screen](https://github.com/user-attachments/assets/79d13581-b025-4d29-8052-6de900ab8688)

#### After Upload Screen

![After Upload Screen](https://github.com/user-attachments/assets/a96ad0db-fe20-425b-963e-ccf4e6b5c789)

#### Download Screen

![Download Screen](https://github.com/user-attachments/assets/3df2401a-2498-447d-a498-9cfcf44b6280)

#### Mail ScreenShot

![Screenshot from 2024-08-19 00-27-13](https://github.com/user-attachments/assets/4e764e68-021c-410d-ba53-af81c426b697)
