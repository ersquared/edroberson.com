# EdRoberson.com V2 — clean replacement

Upload ONLY the contents of this package to the root of your existing GitHub Pages repository.

## Replace V1 without conflicts
1. Back up V1 if desired.
2. Delete the old website files from the repository main branch, but keep the repository.
3. Upload: index.html, assets folder, README.md, CNAME.
4. Commit the changes.
5. Settings > Pages: Deploy from a branch; main; /(root).
6. Custom domain: www.edroberson.com.
7. Enable Enforce HTTPS after GitHub validates DNS.

## Conflict checklist
- Exactly one index.html at repository root.
- No old index.htm or alternate Pages source.
- Pages source is main /(root).
- Only one CNAME file; it contains www.edroberson.com.
- No second GitHub Pages repository uses this custom domain.
- Use Ctrl+F5 or an incognito window if an old cached page appears.

## GoDaddy
Do not change DNS if the current domain already resolves correctly to this same GitHub Pages repository. If it does not, follow GitHub's current official custom-domain instructions rather than guessing DNS values.
