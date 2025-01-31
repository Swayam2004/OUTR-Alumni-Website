## OUTR Alumni Association Website 🎓

A modern web platform for connecting OUTR alumni, built with Express.js, EJS, and Tailwind CSS.

### **Features**

- **User Authentication**
  - Secure login/register system
  - Registration number validation
  - Session management with Passport.js

- **Alumni Directory**
  - Comprehensive alumni profiles
  - Advanced filtering by batch, branch, and name
  - Real-time search functionality
  - LinkedIn integration

- **Responsive Design**
  - Mobile-first approach
  - Modern UI with Tailwind CSS
  - Smooth animations with AOS library
  - Cross-browser compatibility

### **Tech Stack**

- **Backend**
  - Express.js
  - MongoDB with Mongoose
  - Passport.js for authentication
  - EJS templating

- **Frontend** 
  - Tailwind CSS
  - AOS (Animate On Scroll)
  - Font Awesome icons
  - Responsive design

### **Installation**

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/outr-alumni-website.git
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Create .env file and add:
    ```md
    MONGO_URI=your_mongodb_connection_string
    SECRET_KEY=your_session_secret
    ```
4. Start the server:
    ```bash
    npm start
    ```

### **Project Structure**
```bash
├── server/
│   ├── models/
│   │   ├── alumniSchema.js
│   │   └── validRegd.js
│   ├── public/
│   │   ├── js/
│   │   ├── scss/
│   │   └── img/
│   ├── views/
│   │   ├── partials/
│   │   └── *.ejs
│   └── app.js
├── package.json
└── README.md
```

### **Feature Details**
- **Authentication**
  - Secure user registration with registration number validation
  - Password encryption with Passport.js
  - Session management for logged-in users
- **Alumni Directory**
  - Dynamic alumni cards with profile images
  - Detailed modal view for alumni information
  - Advanced filtering and search capabilities
  - LinkedIn profile integration
- **UI/UX**
  - Responsive navigation with mobile menu
  - Animated sections using AOS library
  - Modern card layouts with hover effects
  - Clean and professional design

### **Acknowledgments**
- OUTR Bhubaneswar for support
- All contributing alumni
- Open source community

