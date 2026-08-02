# FoxCo Manager Bot Legal Site

This repository hosts the official public documentation for **FoxCo Manager Bot**, the private operations and management bot used within the **FoxCo Armory & Marketplace (FAM)** Discord server.

## Site contents

| File | Purpose |
|---|---|
| `index.html` | Public landing page for the legal site |
| `terms.md` | FoxCo Manager Bot Terms of Service |
| `privacy.md` | FoxCo Manager Bot Privacy Policy |
| `README.md` | Repository information and publishing instructions |

## Publish with GitHub Pages

1. Upload these files to the root of the repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/(root)` folder.
6. Save the settings and wait for GitHub Pages to deploy the site.

The resulting pages will follow this structure:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/terms/
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/privacy/
```

For a repository named `YOUR-USERNAME.github.io`, omit the repository-name portion:

```text
https://YOUR-USERNAME.github.io/
https://YOUR-USERNAME.github.io/terms/
https://YOUR-USERNAME.github.io/privacy/
```

## Updating the policies

When changing either policy:

1. Update the document's **Last updated** date.
2. Review the landing page for any language that also needs to change.
3. Commit the revision with a descriptive message.
4. Confirm that GitHub Pages successfully redeployed the site.
5. Preserve prior commits so the policy history remains publicly auditable.

## Support

Questions, privacy requests, and data-deletion requests may be sent to:

**foxco.manager.bot.support@gmail.com**

## Security notice

FoxCo Manager Bot may request a Torn API key through its official workflow, but it will never request a Torn password. Credentials should never be sent through ordinary Discord messages, repository issues, or email.

## Disclaimer

FoxCo Manager Bot is an independent community tool and is not sponsored, endorsed, operated by, or affiliated with Discord Inc. or Torn Ltd.

The documents in this repository are operational legal-policy drafts and are not a substitute for advice from a qualified attorney.
