# Privacy Site

Deploy this folder as a static site (Vercel / Netlify / Cloudflare Pages).

Files:
- `index.html` -> Privacy Policy
- `account-deletion.html` -> Account deletion instructions page for Google Play

## Vercel (quick)
1. Go to Vercel dashboard.
2. Add New Project.
3. Import this `privacy-site` folder.
4. Deploy.
5. Copy the HTTPS URL and set it in `mobile/.env`:

```env
EXPO_PUBLIC_PRIVACY_POLICY_URL=https://your-privacy-url
```
