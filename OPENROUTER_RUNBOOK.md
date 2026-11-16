# OpenRouter Auth Runbook (human gate only)

## What the agent cannot do
- Click "Authorize | OpenRouter" on your behalf
- Create a permanent API key inside your OpenRouter account
- Complete OAuth consent for AI Post Studio

## What you do (60 seconds)
1. Open live UI: https://raw.githack.com/cantgetalonggta-png/G0DM0D3-static/main/index.html
2. Click Settings (gear)
3. Either:
   A) **Log in with OpenRouter** → approve the consent screen for the URL above
   B) Paste an OpenRouter key into API Keys field (key stays in browser localStorage only)
4. Set Default Model (e.g. Grok 4.5) and Mode (GODMODE / ULTRAPLINIAN)
5. Send a test message — "No model provider" should clear

## Safety
- Never paste the key into this chat
- Never commit keys to GitHub
- Rotate any key that appeared in logs or chat
- The consent screen URL must be raw.githack.com/.../G0DM0D3-static — that is our keyless deploy

## After auth
- Credits bill to your OpenRouter account
- ULTRAPLINIAN multi-model races will consume multiple model calls
- Privacy: structural metadata optional; turn off in Settings if desired
