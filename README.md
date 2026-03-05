# Board Intelligence say: "Bye Bye Teheran"

A retro-style arcade bombing game with global leaderboards.

## Game Features

- Classic arcade-style bombing gameplay
- Real-time global leaderboard (powered by Firebase)
- Mobile-friendly touch controls
- Retro pixel art aesthetic

## How to Play

- **Arrow Keys / Touch Controls**: Move left and right
- **Spacebar / Red Button**: Drop bombs
- **Objective**: Destroy the bunker core while avoiding SAM missiles and flak

## Deployment

This is a static HTML file that can be deployed to any static hosting service:

### Deploy to Vercel

1. Push this repo to GitHub
2. Visit [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Click "Deploy"

### Firebase Configuration (Optional)

To enable the leaderboard feature, add Firebase environment variables in your Vercel project settings:

- `FIREBASE_CONFIG` - Your Firebase config JSON
- `APP_ID` - Your app identifier
