# 1951DEN Digital Control System — Deployment Guide

## Current release
- Static single-page application: `index.html`
- Netlify configuration: `netlify.toml`
- Brand: 1951DEN
- Founder identity: DEN-Wuttisak.N
- Release: Starter 0.1

## Deploy to Netlify
1. Sign in to Netlify and choose **Add new project → Import an existing project**.
2. Connect the GitHub account and select `wuttisak187-lgtm/Copilot-Microsoft-`.
3. Select branch `main`.
4. Build command: leave blank.
5. Publish directory: `.`
6. Deploy. Netlify will publish the static site and provide a site URL.

`netlify.toml` already specifies the publish directory. This repository has not been connected to a Netlify site by this commit; the Netlify import and first deployment must be completed in the Netlify account.

## Current application scope
- Master dashboard and navigation modules.
- Project, document/IP, digital product, content, and sales registers.
- Add-record form and browser-local persistence.
- JSON and CSV export; JSON import.
- Links to GitHub, Netlify, Gumroad, Canva, YouTube, and Supabase.

## Important limitations
- Data is stored in the current browser's local storage only. It is not a shared cloud database and is not automatically backed up.
- No user authentication, role-based access control, Supabase connection, API integration, automated publishing, or automatic revenue synchronization is configured.
- Platform links are shortcuts only; they do not authorize account access.
- Do not store passwords, API keys, personal sensitive data, or confidential client/project information in this starter application.
- Keep DDP/client project records and 1951DEN intellectual property separate. Publish or commercialize source-project material only after rights and permissions are verified.

## Next production phase
Configure Supabase project, database schema, authentication, access policies (RLS), storage, and application environment variables. Then implement tested API integrations individually. Never put service-role keys or private API secrets in browser code.
