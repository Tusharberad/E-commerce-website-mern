# Next.js E-commerce Web Application

This is a full-stack e-commerce web application built using the **Next.js** framework with **React**, **Express.js** backend, **MongoDB** database, and **Tailwind CSS** for styling. It includes modern libraries like `@react-google-maps/api`, `jsonwebtoken`, and `recharts`.

## 📦 Tech Stack

- **Frontend**: Next.js, React 19, Tailwind CSS
- **Backend**: Express.js
- **Database**: MongoDB with Mongoose
- **Authentication**: JSON Web Tokens (JWT)
- **Styling**: Tailwind CSS
- **Charts**: Recharts
- **Maps**: @react-google-maps/api

---

## 🔧 Project Setup

### Prerequisites

- Node.js (v18 or above recommended)
- MongoDB (local or cloud URI)
- A `.env` file with the following environment variables:

```env
MONGO_URI=mongodb+srv://tinkuberad18:<db_password>@e-commerce441108.cc0cwfu.mongodb.net/
JWT_SECRET=your_jwt_secret


# Clone the repo
git clone =https://github.com/Tusharberad/E-commerce-website-mern

# Install dependencies
npm install

#development
npm run dev

Access the frontend at: http://localhost:3000

Build for Production
npm run build


#Folder Structure

├── app/                 # Next.js App directory (routes, pages)
├── components/          # Reusable UI components
├── pages/               # Page-based routing (if used with app dir)
├── libs/                # Utility libraries and helpers
├── hooks/               # React hooks
├── public/              # Static assets
├── styles/              # Global styles (Tailwind CSS)
├── tailwind.config.js   # Tailwind CSS configuration
├── next.config.ts       # Next.js configuration
├── package.json         # Project dependencies and scripts
└── .gitignore           # Git ignored files




| Command         | Description                |
| --------------- | -------------------------- |
| `npm run dev`   | Run the development server |
| `npm run build` | Create a production build  |
| `npm run lint`  | Lint code with ESLint      |
```
