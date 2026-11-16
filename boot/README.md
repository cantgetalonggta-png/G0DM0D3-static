# Boot package

Machine-readable activator for G0DM0D3 + MRCC. **No API keys in repo.**

## Use
1. Open https://raw.githack.com/cantgetalonggta-png/G0DM0D3-static/main/index.html
2. Settings → Authorize OpenRouter (you must click)
3. Optional: copy `env.template` locally → set OPENROUTER_API_KEY only on your machine

## Files (in session artifacts/boot/)
- BOOT.json — full machine config
- DEBUG_OPTS.json — all developer modes
- boot.sh — probe | oauth | debug | loop
- env.template — safe skeleton

## Truth
- Agent cannot complete OpenRouter OAuth for you (PKCE).
- Never use keys reverse-engineered from APKs.
