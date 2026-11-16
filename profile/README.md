<img src="https://github.com/pgaldev.png?size=144" alt="PGAL" width="72" align="right">

# Welcome to PGAL on GitHub

**DT builds PGAL's custom tools here:** internal web apps, scripts and automations for the firm. This is the home of the `pgaldev` organization, part of PGAL's GitHub Enterprise Cloud account. New to GitHub? Start below, then read the full *PGAL GitHub Getting Started Guide*.

## Quick start (about 15 minutes)

1. **Create a GitHub.com account** at <https://github.com/signup>. A work email is fine.
2. **Turn on two-factor authentication (2FA)** under *Settings → Password and authentication*, using **Microsoft Authenticator**. Save your recovery codes.
3. **Ask PGAL IT for access.** Send them your GitHub username. IT invites you to `pgaldev` and assigns you to the GitHub app in Entra ID.
4. **Accept the invite** from the email or at <https://github.com/pgaldev>.
5. **Authenticate with SSO** using your @pgal.com Microsoft login, then install [GitHub Desktop](https://desktop.github.com) and sign in.

## The everyday loop

**Pull the latest → new branch → edit → commit → push → open a pull request → merge → delete the branch.**
In GitHub Desktop: *Fetch origin* → *Current branch → New branch* → *Commit to branch* → *Publish branch* → *Create Pull Request*. Then on the website: *Merge pull request* → *Delete branch*.

## The rules

- 🔒 **Private repos only.** Public repos need IT/DT approval. Only owners can delete or transfer repos, or change their visibility.
- 🚫 **Never commit passwords, keys, tokens or client data.** Use a `.gitignore` file. If a secret slips in, tell IT right away.
- 🛡️ **`-prod` repos** (for example `intranet-prod`) have a protected `main`: always use a pull request. Force-pushes and deleting `main` are blocked.
- ✍️ **Write clear commit messages**, for example `Fix typo in backup script path`.
- 🤝 **External partners** get access to specific repos only, as outside collaborators. Ask IT.

## Get help

- **PGAL IT** handles access, SSO, invites and partners. Org owners: Anthony Buhnerkemper (IT) and Nick Sticklen.
- **GitHub Docs:** <https://docs.github.com/en/get-started>
- **GitHub Skills (hands-on courses):** <https://skills.github.com>
