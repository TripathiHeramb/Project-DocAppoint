DocAppoint - Doctor Appointment Booking System


## 🏥 Introduction
Prescripto is a comprehensive doctor appointment booking platform that connects patients with healthcare professionals. The platform features a user-friendly interface for patients to book appointments, manage their medical records, and interact with doctors. It includes separate portals for patients, doctors, and administrators.

## 🚀 Features

### For Patients
- User registration and authentication
- Browse and search for doctors
- Book appointments with preferred doctors
- Multiple payment options (Stripe and Razorpay integration)
- View and manage appointments
- Profile management
- Medical history tracking

### For Doctors
- Professional profile management
- Appointment management
- Patient records access
- Schedule management
- Verification system

### For Administrators
- Doctor verification management
- User management
- Platform monitoring
- Analytics and reporting

## 🛠️ Tech Stack

### Frontend
- React.js (v18)
- Vite
- React Router DOM
- Axios for API calls
- TailwindCSS for styling
- React Toastify for notifications

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing
- Cloudinary for image storage
- Payment integrations:
  - Stripe
  - Razorpay

### Admin Panel
- Separate React application
- Tailwind CSS
- Protected routes
- Administrative features

## 📦 Project Structure
```
DocAppoint/
├── frontend/           # Patient and Doctor portal
├── backend/           # API and server logic
└── admin/             # Admin dashboard
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn
- Cloudinary account
- Stripe and Razorpay accounts

### Environment Variables Required

#### Backend
```
PORT=4000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

### Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install Backend Dependencies
```bash
cd backend
npm install
```

3. Install Frontend Dependencies
```bash
cd frontend
npm install
```

4. Install Admin Panel Dependencies
```bash
cd admin
npm install
```

### Running the Application

1. Start the Backend Server
```bash
cd backend
npm run server
```

2. Start the Frontend Application
```bash
cd frontend
npm run dev
```

3. Start the Admin Panel
```bash
cd admin
npm run dev
```

The frontend will run on `http://localhost:5173`
The admin panel will run on `http://localhost:5174`
The backend server will run on `http://localhost:4000`

## 🔒 Security Features
- Password hashing using bcrypt
- JWT authentication
- Protected API routes
- Secure payment processing
- Input validation and sanitization

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

