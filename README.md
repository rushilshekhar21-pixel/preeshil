# Preeshil site

Static site, no build step. Files: `index.html`, `img/`, `vercel.json`.

## Deploy on Vercel

Option A, from the terminal (fastest):
1. Install Node.js, then run `npm i -g vercel`
2. In this folder run `vercel` and accept the defaults (Framework: Other, no build command, output directory `.`)
3. Run `vercel --prod` to publish to the live URL

Option B, from GitHub:
1. Push this folder to a new GitHub repo
2. On vercel.com choose Add New > Project, import the repo
3. Framework Preset: Other. Leave build command empty and output directory as `.`. Deploy.

Add a custom domain under Project > Settings > Domains once you buy one.

## Things to edit in index.html
- `WHATSAPP` in the script at the bottom (currently 919819356687, digits only with country code)
- Prices: search for "INR price to be confirmed" and replace per bag
- Instagram handle and email in the contact block
- Founder name: search for "[Founder name]"
- Remove the "Preview version" line at the bottom when the details are final
