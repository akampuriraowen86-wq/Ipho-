# Owen Lite

A foundation-first short-video app prototype for the Owen project.

## Current foundation
- TikTok-style vertical video feed structure
- Real local video selection
- Search screen wired to stored user data
- User profile screen
- Follow relationship state
- Real local like state starting at zero
- Real local comment state
- Profile statistics start at zero
- No fake likes, followers, comments, or views

## Important limitation
This version is a browser/local prototype. Videos selected from a device use local browser URLs and are not uploaded to a public server. A production version needs authentication, a backend database, cloud video storage, and security rules.

## GitHub Pages
This repository includes a GitHub Actions workflow at `.github/workflows/pages.yml` for deploying the static prototype to GitHub Pages.
