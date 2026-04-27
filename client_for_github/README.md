# SpeedCopy Client Application

React + TypeScript + Vite application for SpeedCopy printing services.

## 🚀 Quick Start

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/snehakoshta/sneha_speedcopy.git
cd sneha_speedcopy

# Install dependencies
npm install

# Create environment file
cp .env.example .env
# Edit .env with your configuration

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173`

## 📦 Build

```bash
# Create production build
npm run build

# Preview production build
npm run preview
```

## 🛠️ Tech Stack

- **React 18** - UI Framework
- **TypeScript** - Type Safety
- **Vite** - Build Tool
- **Tailwind CSS** - Styling
- **React Router** - Routing
- **Axios** - API Client

## 📁 Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Page components
├── services/       # API service layer
├── context/        # React context providers
├── hooks/          # Custom React hooks
├── config/         # Configuration files
└── assets/         # Static assets

public/             # Public assets
```

## 🔧 Configuration

Create a `.env` file based on `.env.example`:

```env
VITE_API_URL=your_api_gateway_url
VITE_RAZORPAY_KEY_ID=your_razorpay_key
VITE_TWILIO_VERIFY_SERVICE_SID=your_twilio_sid
```

## 📝 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🌐 Features

- 🖨️ Printing Services (Documents, Business Cards, etc.)
- 🎁 Gifting Products
- 🛒 Shopping Cart
- 💳 Payment Integration (Razorpay)
- 📱 Phone OTP Authentication
- 👤 User Profile Management
- 💰 Wallet System
- 📦 Order Tracking
- 🎨 Design Editor

## 🔗 Backend Services

This application connects to microservices backend:
- Auth Service
- Product Service
- Order Service
- Payment Service
- Vendor Service

## 📄 License

Private - All Rights Reserved

## 👥 Contact

For questions or support, contact the development team.
