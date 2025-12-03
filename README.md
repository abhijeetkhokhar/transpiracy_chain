# TransparencyChain - Government Funding Transparency Platform

A blockchain-based platform for tracking and verifying government funding allocations across Indian states and union territories with complete transparency and accountability.

## 🎯 Overview

TransparencyChain leverages blockchain technology to create an immutable, transparent record of government funding transactions. The platform enables citizens and stakeholders to monitor fund allocation and utilization across all government departments in real-time.

Key Features

- Blockchain Verification: Every transaction is verified and immutable on the Ethereum blockchain
- Real-time Tracking: Monitor fund allocation and - utilization across all government departments
- Public Access: Citizen-friendly interface providing easy access to government funding information
- Department-wise Tracking: View funding details segregated by departments and states
- Complete Transparency: 100% blockchain-verified transactions with full accountability

## 🏗️ Project Structure

```
src/
├── pages/                          # Main application pages
│   ├── Index.tsx                   # Landing page with transaction overview
│   ├── Login.tsx                   # Web3 wallet connection
│   ├── Dashboard.tsx               # State and UT selection dashboard
│   ├── StateDetail.tsx             # State-level department overview
│   └── DepartmentDetail.tsx        # Department-specific funding details
│
├── components/
│   └── ui/                         # shadcn/ui components (cards, tables, buttons, etc.)
│
├── data/
│   └── indiaData.ts                # States, departments, sample funding data
│
├── hooks/
│   ├── use-toast.ts                # Toast notification hook
│   └── use-mobile.tsx              # Mobile detection hook
│
├── lib/
│   └── utils.ts                    # Utility functions (e.g., className merging)
│
├── styles/
│   ├── index.css                   # Design tokens + Tailwind setup
│   └── App.css                     # Component-specific styles
```

## 📊 Data Structure

indiaData.ts Contains:

- statesAndUTs: 28 States + 8 Union Territories with IDs and types
- departments: 6+ government departments with icons and descriptions
1. Transport Department 🚌
2. Health Department 🏥
3. Education Department 🎓
4. Rural Development 🌾
5. Police Department 👮
6. Public Works Department 🏗️
- sampleFundings: Comprehensive funding transaction data with:
1. Ethereum transaction hashes
2. Receiver/Sender ETH addresses
3. Amounts in both INR and ETH
4. Block numbers and gas details
5. Transaction status tracking

## 🛠️ Tech Stack

- Framework: React with TypeScript
- Build Tool: Vite
- Styling: Tailwind CSS
- UI Components: shadcn/ui
- Routing: React Router v6
- State Management: TanStack Query
- Icons: Lucide React
- Toast Notifications: Custom hook with Radix UI & Sonner
- Form Validation: React Hook Form

## 🚀 Getting Started

Prerequisites
- Node.js 16+ and npm

## Installation 

- git clone [transpiracy_chain](https://github.com/abhijeetkhokhar/transpiracy_chain.git)
- cd transpiracy_chain
- npm install
- npm run dev

### Live Demo
- The application will be available at https://transpiracy-chain.vercel.app/

## 🔐 Blockchain Integration

The platform displays Ethereum transaction details:

- Transaction hashes for verification
- Sender and receiver Ethereum addresses
- Gas usage and pricing information
- Block numbers for traceability
- ETH amount conversions

## 🎯 Features Roadmap

- Real Ethereum blockchain integration
- Web3 wallet connection (MetaMask, WalletConnect)
- Live transaction data from blockchain
- Advanced filtering and search
- Export transaction reports
- Mobile app version
- Multi-language support

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support and questions, please open an issue in the repository.
