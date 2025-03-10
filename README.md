# Pursuit CRM

Pursuit CRM is a restaurant-focused Customer Relationship Management (CRM) system designed to seamlessly integrate with existing restaurant websites. It helps restaurant owners manage customer interactions, reservations, feedback, and marketing campaigns efficiently.

## Features

- **Customer Management**: Store and manage customer details, preferences, and visit history.
- **Reservation System**: Allow customers to make reservations directly through the restaurant's website.
- **Order & Feedback Tracking**: Keep track of past orders and customer feedback for better service.
- **Automated Marketing**: Engage customers with automated email and SMS campaigns.
- **Analytics & Reports**: Generate insightful reports on customer behavior and sales trends.
- **Multi-Restaurant Support**: Manage multiple restaurant locations from a single dashboard.
- **Role-Based Access**: Admin, Manager, and Staff roles with different levels of access.

## Tech Stack

- **Frontend**: React.js, TailwindCSS
- **Backend**: Golang (Gin Framework, sqlc)
- **Database**: PostgreSQL
- **Authentication**: Supabase Auth
- **Messaging**: Twilio (for SMS), SendGrid (for emails)
- **Hosting & Deployment**: AWS (EC2, RDS, S3)

## Installation

### Prerequisites
Ensure you have the following installed:
- Go 1.18+
- Node.js 16+
- PostgreSQL

### Backend Setup
```bash
git clone https://github.com/samama251251/pursuit.git
cd pursuit/backend
go mod tidy

go run main.go
```

### Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```
\
