# Discord Bot

A feature-rich Discord bot built with Discord.js

## Features

- Admin commands (ban, kick, mute, etc.)
- Chat management (auto-reply, slowmode, etc.)
- User roles and permissions
- Security features (anti-spam, anti-bot, etc.)
- Voice channel management
- Ticket system
- And many more!

## Prerequisites

- Node.js 18+
- Discord Bot Token
- Git

## Local Setup

1. Clone the repository
```bash
git clone <your-repo-url>
cd system
```

2. Install dependencies
```bash
npm install
```

3. Create `.env` file based on `.env.example`
```bash
cp .env.example .env
```

4. Add your Discord bot token to `.env`
```
DISCORD_TOKEN=your_token_here
```

5. Start the bot
```bash
npm start
```

## Deployment to Railway

### Prerequisites
- Railway account (https://railway.app)
- Railway API token

### Steps

1. Login to Railway CLI
```bash
railway login
```

2. Initialize Railway project
```bash
railway init
```

3. Link your project
```bash
railway link
```

4. Deploy
```bash
railway up
```

5. Set environment variables in Railway dashboard:
   - DISCORD_TOKEN
   - Any other required API keys

## GitHub Deployment (Auto-Deploy)

1. Push your code to GitHub
2. Go to your repository settings
3. Add secrets:
   - RAILWAY_TOKEN (your Railway API token)
4. The workflow will automatically deploy on push to main branch

## Commands

- `npm start` - Start the bot
- `npm run dev` - Start in development mode (if configured)

## Support

For issues, create a GitHub issue or contact the developer.

## License

MIT
