# Security Notes

No public website can be guaranteed to be "absolutely secure" or "never hacked."
However, this site is designed to minimize risk through a very small attack surface.

## What makes this version safer
- Pure static HTML + CSS
- No backend server
- No database
- No user login system
- No forms or file uploads
- No third-party JavaScript
- No analytics trackers
- No cookies
- No build pipeline required for deployment
- `.nojekyll` included to keep GitHub Pages deployment simple
- Content Security Policy set via a meta tag to disable scripts and risky embedded content

## Remaining risks you still need to manage
- Protect your GitHub account with a strong password and 2FA
- Do not expose private emails/phone numbers unless you are comfortable with that
- Review all external links before publishing
- Keep the repository itself under your control

## Best deployment choice
For the lowest risk, use **GitHub Pages with a static site only**.
Avoid adding:
- contact forms backed by external services
- comment systems
- ad scripts
- random JavaScript widgets
- unnecessary tracking code
