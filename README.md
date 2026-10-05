# booleanaxis.com

Static site for Boolean Axis, served by GitHub Pages.

- `index.html` — the whole page (inline CSS, no build step)
- `CNAME` — custom domain for GitHub Pages; don't delete it
- `.nojekyll` — serve files as-is

Deploy: commit and `git push`; Pages republishes within a minute.

## DNS (Squarespace → Domains → booleanaxis.com)

Website records only — leave MX, SPF and `google._domainkey` alone, they carry Workspace mail.

| Host | Type | Value |
|---|---|---|
| @ | A | 185.199.108.153 |
| @ | A | 185.199.109.153 |
| @ | A | 185.199.110.153 |
| @ | A | 185.199.111.153 |
| www | CNAME | `umairrafiq.github.io` |
