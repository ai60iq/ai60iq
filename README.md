# ai60iq

## Set Up the Character Files

Open ```src/character.ts``` to modify the default character. Uncomment and edit.
## Use Custom Characters
- Start the app with your custom character file(s):
- ```pnpm start --characters="path/to/your/character.json"```

 

## Add client

in character.ts
- ```clients: [Clients.TWITTER, Clients.DISCORD],```

in character.json
- ```clients: ["twitter", "discord"]```

## Configure Environment Variables

### Copy the Environment Template
- ```cp .env.example .env```

   Fill Out the .env File

## Replace placeholder values with your credentials:

```DISCORD_APPLICATION_ID="your-discord-app-id"
DISCORD_API_TOKEN="your-discord-api-token"

OPENROUTER_API_KEY="sk-xx-xx-xxx"

TWITTER_USERNAME="your-twitter-username"
TWITTER_PASSWORD="your-twitter-password"
TWITTER_EMAIL="your@email.com"
```

## Install Dependencies and Start the Agent
### Install Required Packages
```pnpm i && pnpm start```

Note: this requires node to be at least version 22 when you install packages and run the agent.
