# TestProject

Project description goes here.

## Auto-Deploy Setup

This project includes automatic deployment to GitHub. To use:

1. Start auto-deploy:
   ```bash
   npm run watch
   ```

2. Or make manual deployments:
   ```bash
   npm run deploy --message="your update message"
   ```

The auto-deploy will:
- Monitor for changes every 3 seconds
- Automatically commit and push changes
- Include timestamps in commit messages
