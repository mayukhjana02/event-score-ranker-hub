# Event Score Ranker Hub 🏆

**Advanced TypeScript Event Management & Ranking System**

## Overview

Event Score Ranker Hub is a sophisticated event management and ranking platform that provides real-time scoring, leaderboards, and comprehensive analytics. Built with cutting-edge TypeScript, React, and modern backend technologies, it's perfect for tournaments, competitions, and any scenario requiring event-based ranking systems.

## Key Features

### Core Functionality
- 🏅 **Dynamic Ranking System**: Real-time score calculations and leaderboard updates
- 📊 **Advanced Analytics**: Comprehensive event statistics and performance metrics  
- 🚀 **High Performance**: Optimized for handling large-scale events with thousands of participants
- 🔄 **Real-time Updates**: WebSocket-based live score streaming
- 💾 **Data Persistence**: Robust database integration with Supabase
- 🎨 **Modern UI/UX**: Beautiful, responsive interface built with React and Shadcn UI
- 🔒 **Type-Safe**: 100% TypeScript for maximum reliability
- 🛡️ **Secure**: Built-in authentication and authorization

### Technical Highlights
- **Microservices Architecture**: Scalable and maintainable codebase
- **RESTful API**: Clean, documented endpoints
- **Real-time Leaderboards**: Instant rank updates
- **Custom Scoring Algorithms**: Flexible point calculation systems
- **Event Categories**: Support for multiple event types and categories
- **Historical Data**: Complete event history and analytics

## Tech Stack

### Frontend
- **React** - Modern UI library
- **TypeScript** - Type-safe development
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn UI** - Beautiful component library
- **React Query** - Powerful data fetching

### Backend
- **Node.js** - Server runtime
- **Express** - Web framework
- **TypeScript** - Type safety throughout
- **Supabase** - Backend-as-a-Service
- **PostgreSQL** - Relational database

### DevOps & Tools
- **ESLint** - Code quality
- **Prettier** - Code formatting
- **Git** - Version control
- **Docker** - Containerization ready

## Getting Started

### Prerequisites
```bash
Node.js 18+
npm or yarn
Supabase account (for backend)
```

### Installation

```bash
# Clone the repository
git clone https://github.com/mayukhjana02/event-score-ranker-hub.git
cd event-score-ranker-hub

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your Supabase credentials

# Start development server
npm run dev
```

The application will be available at `http://localhost:5173`

### Environment Variables

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Project Structure

```
event-score-ranker-hub/
├── src/
│   ├── components/       # React components
│   │   ├── ui/           # Reusable UI components
│   │   └── features/     # Feature-specific components
│   ├── pages/            # Page components
│   ├── hooks/            # Custom React hooks
│   ├── services/         # API services
│   ├── types/            # TypeScript type definitions
│   ├── utils/            # Utility functions
│   └── lib/              # Third-party library configs
├── public/              # Static assets
├── tests/               # Test files
└── config/              # Configuration files
```

## API Endpoints

### Events
- `GET /api/events` - List all events
- `POST /api/events` - Create new event
- `GET /api/events/:id` - Get event details
- `PUT /api/events/:id` - Update event
- `DELETE /api/events/:id` - Delete event

### Scores
- `GET /api/scores/:eventId` - Get event scores
- `POST /api/scores` - Submit score
- `PUT /api/scores/:id` - Update score
- `GET /api/leaderboard/:eventId` - Get leaderboard

### Rankings
- `GET /api/rankings/:eventId` - Get current rankings
- `GET /api/rankings/live/:eventId` - WebSocket for live updates

## Features in Detail

### Real-time Leaderboards
Experience instant rank updates as scores change. Perfect for live competitions and tournaments.

### Custom Scoring Rules
Define your own scoring algorithms with flexible point systems, multipliers, and bonuses.

### Event Management
Create, manage, and track multiple events simultaneously with comprehensive dashboards.

### Analytics & Insights
Gain deep insights into participant performance with detailed statistics and visualizations.

## Performance

- ⚡ Fast page loads (<1s)
- 📊 Handles 10,000+ concurrent users
- 🚀 Real-time updates with minimal latency
- 🎯 Sub-100ms API response times

## Development

```bash
# Run development server
npm run dev

# Build for production
npm run build

# Run tests
npm test

# Lint code
npm run lint

# Format code
npm run format
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

MIT License - feel free to use this project for personal and commercial purposes.

## Author

**Mayukh Jana**  
Full-Stack AI/ML Engineer & Backend Developer

- GitHub: [@mayukhjana02](https://github.com/mayukhjana02)
- LinkedIn: [mayukhjana](https://linkedin.com/in/mayukhjana)
- Portfolio: [mayukhjana.dev](https://mayukhjana.dev)
- Twitter: [@mayukhjana02](https://twitter.com/mayukhjana02)

## Acknowledgments

- Built with modern TypeScript and React
- Powered by Supabase for backend services
- UI components from Shadcn UI
- Styled with Tailwind CSS

---

**⭐ If you find this project useful, please consider giving it a star!**

**Built with ❤️ and TypeScript by Mayukh Jana**
