# StyleAI — Phase 1

Mobile-first Next.js foundation for an AI hairstyle/beard web app.

## Included
- Next.js + TypeScript + Tailwind
- Firebase Auth wiring (Google + email/password)
- 12 hairstyle categories
- 120 generated hairstyle catalog entries
- Beard/shaving catalog
- Mobile upload validation + client-side preview compression
- Demo-mode ImageProcessingService abstraction
- Dashboard + editor shell
- Privacy + Terms templates

## Run
1. Install Node.js.
2. `npm install`
3. Copy `.env.example` to `.env.local`.
4. Add Firebase Web App config.
5. Enable Google and Email/Password providers in Firebase Authentication.
6. `npm run dev`

## Important
This is a Phase 1 foundation, not a production launch.
A real AI image provider, production privacy/terms, secure server-side processing, storage rules, ads provider, and production testing must be completed before launch.

## Mobile-only note
If you are working entirely from Android, use a browser-based development environment such as GitHub Codespaces or another compatible cloud IDE. Do not paste secret API keys into public repositories.
