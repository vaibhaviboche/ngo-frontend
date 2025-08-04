# NGO Application Portal

This is a full-stack web project to manage volunteer applications for an NGO.

## Features

- Volunteers can submit an application form  
- Admin can log in securely  
- Admin can view, approve, or reject applications  
- Admin can filter applications by status  
- Admin can export applications as a CSV file  

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JSON Web Token (JWT)  
- **Deployment**: Render (Backend), Netlify (Frontend)  

## Live Links

- **Backend (Render)**: https://ngo-backend-duzs.onrender.com  
- **Frontend (Netlify)**: https://ngo-site-vaibhavi.netlify.app/  
- **GitHub Repo**: https://github.com/vaibhaviboche/ngo-backend  

## How to Run the Project Locally

### Backend

1. Open terminal or command prompt  
2. Go to the backend folder:  
   cd server  
3. Install dependencies:  
   npm install  
4. Start the server:  
   npm start  

> ⚠️ Make sure you have a `.env` file with:
> ```
> MONGO_URI=your_mongodb_connection_string
> JWT_SECRET=your_jwt_secret
> ```

### Frontend

1. Open `client/index.html` in your browser  

## Admin Login Credentials

Email: admin@ngo.com  
Password: admin123

## License

MIT License
