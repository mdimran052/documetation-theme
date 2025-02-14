---
layout: default
---

## Welcome to Github Considerations Page

_yay_

## Key Considerations for GitHub Pages in Enterprise

**Availability in GitHub Enterprise Cloud Only**

GitHub Pages is not available in GitHub Enterprise Server (on-premise).
It is available in GitHub Enterprise Cloud.

**Private Repositories Support**

If you are using a GitHub Free or Pro account, GitHub Pages is only available for public repositories.
However, GitHub Enterprise Cloud and GitHub Team accounts allow private repositories to host GitHub Pages.

**Access Control for Private Pages**

Pages hosted from private repositories are always private and can only be accessed by authenticated users with the right permissions.
GitHub does not support publishing a private repository’s GitHub Pages site publicly.

**Build Process and Security**

Private repository Pages must be built using GitHub Actions or a local Jekyll build before deployment.
GitHub disables automatic builds for security reasons in private repositories.

[back](./)
