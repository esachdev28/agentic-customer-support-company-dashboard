# Agentic Customer Support Dashboard

A professional, real-time analytics dashboard for monitoring agentic customer support interactions. This dashboard provides deep insights into conversation volumes, sender distribution, sentiment trends, and resolution metrics, all powered by Supabase and Vite.

![Dashboard Preview](https://github.com/esachdev28/agentic-customer-support-company-dashboard/raw/main/src/assets/hero.png)

## 🚀 Features

- **Real-time Metrics**: Live updates of conversation counts and sender types (User, Bot, Agent, Escalations).
- **Conversation Logs**: Filterable live feed of all support messages with sender-specific styling.
- **Interactive Charts**:
  - **Volume Trends**: Message volume over time using `Recharts`.
  - **Sender Distribution**: Visual breakdown of who is handling your support requests.
- **Advanced Filtering**: Filter data by sender type and date ranges (24h, 7d, 30d, All Time).
- **Supabase Integration**: Real-time Postgres subscriptions for instant dashboard updates.
- **Modern UI/UX**: Sleek dark-mode interface built with Tailwind CSS, featuring glassmorphism and smooth animations.

## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite 8](https://vitejs.dev/)
- **Styling**: [Tailwind CSS 3](https://tailwindcss.com/)
- **Database/Real-time**: [Supabase](https://supabase.com/)
- **Charts**: [Recharts](https://recharts.org/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Date Handling**: [date-fns](https://date-fns.org/)

## 📁 Project Structure

```text
├── src/
│   ├── components/
│   │   ├── Dashboard.jsx    # Main metrics and analytics view
│   │   ├── Sentiment.jsx    # Sentiment analysis visualization
│   │   ├── Resolution.jsx   # Ticket resolution performance
│   │   └── Layout.jsx       # Global sidebar and navigation wrapper
│   ├── assets/              # Static assets and images
│   ├── supabaseClient.js    # Supabase connection configuration
│   ├── App.jsx              # Main routing and page state management
│   ├── main.jsx             # React application entry point
│   └── index.css            # Global styles and Tailwind imports
├── public/                  # Static assets (icons, favicons)
├── tailwind.config.js       # Tailwind CSS configuration
├── vite.config.js           # Vite build configuration
└── package.json             # Project dependencies and scripts
```

## ⚙️ Getting Started

### Prerequisites
- Node.js 22.0.0 or higher
- npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/esachdev28/agentic-customer-support-company-dashboard.git
   cd agentic-customer-support-company-dashboard
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```
   The dashboard will be available at `http://localhost:5173/`.

### Deployment

To build the project for production:
```bash
npm run build
```
The output will be in the `dist/` directory, ready to be hosted on Vercel, Netlify, or any static hosting service.

## 🛡️ License

This project is licensed under the MIT License - see the LICENSE file for details.

---
Built with ❤️ for Agentic Support Teams.
