# Smart Contact Manager

Smart Contact Manager is a full-stack web application designed to manage and organize your contacts efficiently. Built using **Node.js**, **Express.js**, **MongoDB**, and modern frontend technologies, this application offers a user-friendly interface for creating, updating, and managing contacts.

---

## Features

- **User Authentication**: Secure user login and registration using JWT.
- **Contact Management**: Add, edit, delete, and view contacts.
- **Search Functionality**: Easily search through your contact list.
- **Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **User Dashboard**: Personalized dashboard to manage your contacts.
- **Role-based Access**: Admin and user-specific features.

---

## Demo

[Live Demo Link](#)  
*(Replace this with the link to your deployed app)*

---

## Tech Stack

### Backend
- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for data storage.

### Frontend
- **EJS (Embedded JavaScript)**: Templating engine for dynamic web pages.
- **Bootstrap**: CSS framework for responsive design.
- **Vanilla JavaScript**: For frontend interactivity.

---

## Installation and Setup

Follow these steps to set up the project locally:

### Prerequisites

- Node.js (v14+)
- MongoDB
- Git

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/smart-contact-manager.git
   cd smart-contact-manager
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```
   PORT=5000
   MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/smartContactManager?retryWrites=true&w=majority
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the application**:
   ```bash
   npm start
   ```
   The app will be available at [http://localhost:5000](http://localhost:5000).

---

## Project Structure

```
smart-contact-manager/
├── public/           # Static files (CSS, JS, Images)
├── routes/           # Express routes
├── views/            # EJS templates
├── models/           # Mongoose models
├── controllers/      # Controller logic
├── app.js            # Main entry point
├── .env              # Environment variables
├── package.json      # Dependencies and scripts
```

---

## API Endpoints

### User Authentication
- **POST** `/api/auth/register`: Register a new user.
- **POST** `/api/auth/login`: User login.

### Contacts
- **GET** `/api/contacts`: Fetch all contacts for the logged-in user.
- **POST** `/api/contacts`: Add a new contact.
- **PUT** `/api/contacts/:id`: Update a contact.
- **DELETE** `/api/contacts/:id`: Delete a contact.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-branch
   ```
5. Submit a pull request.


---

Replace placeholders like `your-username`, `your_jwt_secret`, and other details with your project-specific information.

