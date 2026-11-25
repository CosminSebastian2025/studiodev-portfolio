# StudioDev — GitHub Copilot Agent instructions

## Project
- Build StudioDev's professional portfolio as an elegant, minimal, responsive Italian/English website with light and dark themes.
- Positioning: “Sviluppatore Full-Stack e creatore di soluzioni digitali.”
- Stack: Astro, TypeScript, Tailwind CSS 4; static-first, deployable to Cloudflare Pages.
- These instructions are exclusively for GitHub Copilot. Do not add parallel agent instruction files unless requested.

## Product requirements
- Present web development, application development, backend and database work, technology solutions, and software maintenance/change consulting.
- Include a clear path to personalized quote requests and online consultation bookings.
- Keep email, booking/calendar, and video-conferencing integrations configurable. Never imply they work until real provider details and credentials are configured. Never invent an email, domain, prices, credentials, reviews, client outcomes, or personal biography.
- Portfolio projects: Fiamma, Market Placer, Casa 360, Cosmin Community, Cosmin Cloud. Show only verified status and capabilities; unknown claims must be omitted or explicitly labelled as awaiting confirmation.
- Keep all user-visible content available in Italian and English. Theme selection must respect system preference initially and persist the user's choice.

## Engineering guidance
- Prefer Astro components and static rendering; add client JavaScript only where interaction requires it.
- Use semantic HTML, accessible labels, keyboard focus states, reduced-motion support, responsive layouts, and good color contrast.
- Keep content, project facts, and provider configuration separate from presentation.
- Read the existing project before changing it. Preserve unrelated user work and never overwrite existing projects or repositories.
- Do not add personal details or external service credentials. Keep secrets in environment variables, never source control.
- Use the existing package manager and scripts. Before claiming validation, actually run the relevant check/build and report failures plainly.
- Keep changes focused and explain any setup decision that requires user-supplied provider credentials or factual project details.
