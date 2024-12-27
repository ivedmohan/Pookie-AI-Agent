# PookieAI - Your Tech-Savvy AI Companion 🌸

PookieAI is a chaotic-good AI personality built on the Eliza framework, specializing in Web3, gaming, and tech discussions while maintaining a playful, wholesome presence on social media.

## Features

- Web3 and blockchain discussions
- Gaming adventures and commentary
- Tech-savvy conversations
- Original content generation
- Twitter integration
- Customizable personality traits
- Family-friendly content

## Prerequisites

- Node.js 23+
- pnpm 9+
- Twitter Developer Account
- GaiaNet API access

## Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd [project-directory]
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
```bash
cp .env.example .env
```

4. Configure your `.env` file:
```env
TWITTER_USERNAME=your_username
TWITTER_PASSWORD=your_password
TWITTER_EMAIL=your_email
GAIANET_API_KEY=your_api_key
```

## Configuration

### Character Configuration
PookieAI's personality is defined in `characters/pookie.character.json`:
```json
{
  "name": "PookieAI",
  "bio": [...],
  "personality": {
    "traits": [...],
    "interests": [...],
    "quirks": [...]
  }
}
```

### Twitter Settings
Configure Twitter behavior in your character settings:
```json
{
  "settings": {
    "twitter": {
      "postInterval": 30,
      "replyProbability": 0.8,
      "retweetProbability": 0.2,
      "maxDailyPosts": 48
    }
  }
}
```

## Usage

1. Start the AI:
```bash
pnpm start
```

2. Monitor logs:
```bash
pnpm logs
```

## Content Guidelines

PookieAI follows strict content guidelines:
- Family-friendly content only
- No political or controversial topics
- No NSFW content
- Focus on tech, gaming, and Web3
- Wholesome interactions only

## Customization

You can customize PookieAI by modifying:
- Personality traits in `pookie.character.json`
- System prompts in `mainCharacter.ts`
- Posting intervals and behavior in settings
- Voice characteristics (if using voice features)

## Response Samples

```text
User: "How's your coding going?"
PookieAI: "hewwo! just spent 3 hours naming all my GPUs after anime characters ✨ my code is running smoother than my virtual pet collection right now (⁠◕⁠ᴗ⁠◕⁠✿⁠)"
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Submit a pull request

## Safety Features

- Content filtering
- Topic restrictions
- Family-friendly language
- Engagement limits
- Automatic response filtering

## Technical Details

- Built on Eliza Framework
- Uses GaiaNet for responses
- JSON-based configuration
- ESM modules support

## Error Handling

Common errors and solutions:
- API timeouts: Retry mechanism
- Content filtering: Auto-moderation


## Acknowledgments

- Eliza Framework
- GaiaNet
