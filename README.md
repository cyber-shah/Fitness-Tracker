# FitTrack - Fitness Tracker Web App

A comprehensive fitness tracking application with workout logging, progress charts, goals, custom workout plans, and more.

## Features

- 📊 **Dashboard** - Overview of your fitness journey
- 💪 **Workout Logging** - Track gym and cardio workouts
- 📈 **Progress Charts** - Visualize your improvements
- 🎯 **Goals** - Set and track fitness goals
- 📋 **Workout Plans** - Beginner, Intermediate, Advanced, or Custom
- 📑 **Reports** - Weekly, monthly, and all-time summaries
- 🏆 **Personal Records** - Track your best performances
- 📊 **Body Stats** - BMI tracking and body composition
- 🏅 **Achievements** - Unlock badges and milestones
- ⏰ **Reminders** - Daily workout notifications

## Deployment to Netlify

### Option 1: Drag and Drop (Easiest)
1. Download all files in this folder
2. Go to [Netlify](https://www.netlify.com/)
3. Sign up or log in
4. Drag the entire folder onto the Netlify dashboard
5. Your site will be live in seconds!

### Option 2: Git Deploy
1. Create a new repository on GitHub
2. Upload all these files to your repository
3. Connect your GitHub repo to Netlify
4. Netlify will auto-deploy on every push

### Option 3: Netlify CLI
```bash
npm install -g netlify-cli
netlify deploy
```

## File Structure

```
fitness-tracker-app/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   ├── app.js          # Main application logic
│   ├── storage.js      # LocalStorage management
│   ├── workouts.js     # Workout logging & display
│   ├── goals.js        # Goals management
│   ├── plans.js        # Workout plans
│   ├── charts.js       # Chart rendering
│   ├── body.js         # Body measurements & BMI
│   ├── achievements.js # Achievement system
│   ├── reports.js      # Report generation
│   └── records.js      # Personal records tracking
└── README.md           # This file
```

## Local Development

Simply open `index.html` in your browser. No build process required!

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Data Storage

All data is stored locally in your browser using LocalStorage. Your data never leaves your device.

## Support

For issues or questions, please open an issue on GitHub.

## License

MIT License - Feel free to use and modify!
