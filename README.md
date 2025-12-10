# Prism

A full-stack web application for managing clients, projects, contacts, and newsletters.

## Features

- **Client Management**: Add, view, and manage client information
- **Project Management**: Organize and track projects with details
- **Contact Forms**: Handle customer inquiries and contact submissions
- **Newsletter Subscription**: Manage newsletter subscribers
- **Admin Dashboard**: Comprehensive admin panel for managing all aspects

## Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- PostCSS
- JavaScript/JSX

### Backend
- Node.js
- Express.js
- MongoDB (models included)
- Multer (file uploads)

## Project Structure

```
├── frontend/           # React frontend application
│   ├── src/
│   │   ├── components/ # React components
│   │   ├── pages/      # Page components
│   │   ├── api/        # API integration
│   │   └── utils/      # Utility functions
│   ├── package.json
│   └── vite.config.js
│
└── backend/            # Node.js backend server
    ├── controllers/    # Route controllers
    ├── models/         # Database models
    ├── routes/         # API routes
    ├── config/         # Configuration files
    └── server.js       # Main server file
```

## Installation

### Backend Setup
```bash
cd backend
npm install
```

### Frontend Setup
```bash
cd frontend
npm install
```

## Running the Application

### Backend
```bash
cd backend
npm start
```

### Frontend
```bash
cd frontend
npm run dev
```

## API Endpoints

- **Clients**: `/api/clients`
- **Projects**: `/api/projects`
- **Contacts**: `/api/contacts`
- **Newsletter**: `/api/newsletter`

## File Uploads

File uploads are configured using Multer. Uploaded files are stored in the `backend/uploads/` directory.

## Environment Variables

Create a `.env` file in the backend directory with necessary configuration variables.

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.
