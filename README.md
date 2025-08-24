# OdinProject_MiniDrive
Node JS Course Project: File Upload


Set up a new project using Express and Prisma. Install all the necessary dependencies including Passport etc.
Set up session based authentication using Passport.js. Use the Prisma session store library to persist sessions in the database.
Add a form where authenticated users can upload a file. Save the file in your filesystem for now. You’ll need to integrate the multer middleware. We’ll upload these files once we have all other features working.
Add folders. Users should be able to CRUD folders and upload files in them. Set up routes and necessary database interactions for this.
Add a route to view specific file details like name, size, and upload time. There should be a download button to allow users to download the file.
Finally, add logic to upload files. You could store it in a database, but it’s advised to use a cloud storage service for this usecase. You can use Cloudinary or Supabase storage. When a file is uploaded, save the file URL in the database.
