# Research proof: remaining gates are by design

## OpenRouter OAuth (Authorize button)
- Source: https://openrouter.ai/docs/guides/overview/auth/oauth
- Flow is **PKCE**: user is sent to OpenRouter `/auth`, must **log in and authorize the app**, then callback returns a code exchanged for a **user-controlled API key**.
- That key is meant to live in the **browser** (or your DB) — not on the G0DM0D3 static host.
- **Agent cannot click Authorize** for your Personal account. This is correct security, not a deploy failure.

## Vercel project create 403
- Source: https://vercel.com/docs/rbac/access-roles and create-project docs
- Creating a project requires **Owner/Member** or Developer + **Create Project** extended permission.
- API `forbidden` = token/role cannot create projects on the team.
- **Workaround that works forever:** Import `cantgetalonggta-png/G0DM0D3-static` in the Vercel dashboard, OR keep the GitHub + raw.githack CDN URL (already production HTTP 200).

## What is already complete
- Static SPA live: https://raw.githack.com/cantgetalonggta-png/G0DM0D3-static/main/index.html
- Keyless, AGPL upstream, no secrets in repo
- MRCC claimed swarm surface live
- BG20 learning package in session artifacts

## Your only required actions
1. Open live G0DM0D3 → Settings → **Authorize | OpenRouter**
2. Optional: Vercel Import Project for `*.vercel.app` hostname
