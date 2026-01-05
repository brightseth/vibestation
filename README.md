# Vibestation

CRT retro hardware guide for vibe coders. Part of the vibecodings ecosystem.

## Live

- **Main**: https://vibestation-guide.vercel.app
- **Quiz**: https://vibestation-guide.vercel.app/vibestation-quiz
- **Brand**: https://vibestation-guide.vercel.app/vibestation-brand
- **Logos**: https://vibestation-guide.vercel.app/vibestation-logos

## Ecosystem

```
vibecodings.vercel.app  ─── Directory (hub)
slashvibe.dev           ─── Social layer (/vibe)
vibestation-guide.vercel.app ─── This project
```

## Docs

- `docs/BRAND_BIBLE.md` - Visual identity, colors, typography
- `docs/USER_FLOWS.md` - User journey diagrams
- `docs/ECOSYSTEM_PLAN.md` - Full ecosystem architecture

## Stack

- Static HTML + CSS
- Phosphor green (#33FF33) + amber (#FFB000) palette
- IBM Plex Mono + VT323 typography
- CRT scanline effects

## Development

```bash
# Local preview
npx serve .

# Deploy
vercel --prod
```

## Related Repos

- [vibecodings](https://github.com/brightseth/vibecodings) - Project directory
- [vibe-public](https://github.com/sethvibes/vibe-public) - /vibe social layer
