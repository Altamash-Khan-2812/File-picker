# User Profiles Uploader (File Picker)

This is a simple demo project built with **Node.js**, **Express**, **EJS**, and **MongoDB**.  
It demonstrates how to **handle file uploads (images)** on the backend using **Multer**, and store user data in a MongoDB database.


##  Features

- Add new users with profile images  
- Store uploaded images in the `images/` folder  
- Save user data (name and image path) in MongoDB  
- Display all uploaded users on the home page  
- Simple and clean EJS-based frontend

## Project Structure
<img src="/Project-Structure.png" />

##  Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Templating Engine:** EJS  
- **File Upload Handling:** Multer  
- **Styling:** Basic CSS (served from `public/` folder)



##  Installation & Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/user-profiles-upload.git
   cd user-profiles-upload
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up MongoDB**
   - Create a local MongoDB database named `users-demo` (or update your connection URL in `data/database.js`).

4. **Run the server**
   ```bash
   node app.js
   ```
   Server will start at **http://localhost:3000**

---

##  Usage

1. Go to `http://localhost:3000/new-user`  
2. Enter a username and upload an image  
3. Submit the form  
4. You’ll be redirected to the homepage showing all users with their uploaded images