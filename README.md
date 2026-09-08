# Blood Bank Website

A modern web application built with **Next.js** for managing blood donations and requests. This platform connects blood donors with those in need of blood transfusions.

## Features

- **Donor Login**: For blood donors to register, manage their profile, and track donation history
- **Requester Login**: For patients/hospitals to request blood and check availability
- **User Authentication**: Secure login system for both donor and requester roles
- **Responsive Design**: Mobile-friendly interface built with modern UI components
- **Real-time Updates**: Track blood availability and donation requests

## Tech Stack

- **Frontend Framework**: Next.js 14+
- **Styling**: Tailwind CSS
- **Authentication**: NextAuth.js (optional - can be customized)
- **Database**: MongoDB / PostgreSQL (to be configured)
- **Language**: JavaScript/TypeScript

## Project Structure

```
blood-bank-nextjs/
├── app/
│   ├── page.js                 # Homepage
│   ├── donor/
│   │   ├── login/             # Donor login page
│   │   ├── register/          # Donor registration
│   │   └── dashboard/         # Donor dashboard
│   ├── requester/
│   │   ├── login/             # Requester login page
│   │   ├── register/          # Requester registration
│   │   └── dashboard/         # Requester dashboard
│   └── layout.js              # Root layout
├── components/                # Reusable React components
├── public/                    # Static assets
├── styles/                    # Global styles
└── package.json              # Dependencies
```

## Getting Started

### Prerequisites

- Node.js 16.x or higher
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kashish181106/blood-bank-nextjs.git
cd blood-bank-nextjs
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env.local` file with your environment variables:
```bash
NEXT_PUBLIC_API_URL=your_api_url
DATABASE_URL=your_database_url
```

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

### For Donors
- Navigate to the homepage and click "Login as Donor"
- Create an account or login with existing credentials
- Access your dashboard to manage your profile and donation history

### For Requesters
- Navigate to the homepage and click "Login as Requester"
- Create an account or login with existing credentials
- Request blood and check real-time availability

## Development

### Build for production:
```bash
npm run build
npm start
```

### Run tests:
```bash
npm test
```

### Linting:
```bash
npm run lint
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, email support@bloodbank.com or open an issue in the repository.

---

**Made with ❤️ to save lives**
