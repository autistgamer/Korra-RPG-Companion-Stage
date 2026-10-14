# Korra RPG Companion Stage v0.1

Companion Stage for the "Legend of Korra RPG" character card on chub.ai.

## Features (v1)
- Real 2d6 dice resolution (F1)
- Character sheet + tracker panel (F2)
- In-world clock + background event deck (F3)
- Group-chat safety (F4)

## How to publish to Chub
1. Create a new empty GitHub repository.
2. Upload / push the contents of this folder to it.
3. Go to https://chub.ai/my_stages?active=tokens and create a write token.
4. In your GitHub repo: Settings → Secrets and variables → Actions → New repository secret
   - Name: `CHUB_AUTH_TOKEN`
   - Value: the token you just created
5. Push any change (or re-run the workflow under Actions). The stage will appear in your Chub stages list.

## Attach to the card
In the character editor or in a chat’s Chat Settings → Stages, add “Korra RPG Companion”.

The card remains fully usable without the Stage.
