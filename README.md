# Nexora Systems — Active Directory Security Lab

Static project showcase for an isolated Windows Active Directory training lab.

## Current status
- Core lab setup verified: `nexora.local`, DC01, domain-joined WS01
- OUs, users, security groups, `svc_sql` account and SPN configured
- `NexoraShare` created and accessed successfully from WS01
- Attack-path validation is **pending**; do not claim the attack paths are completed until tested and evidenced

## GitHub Pages deployment
1. Create a public GitHub repository named `nexora-ad-security-lab` (or another available name).
2. Upload `index.html` and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, select **Deploy from a branch**.
5. Choose branch `main` and folder `/(root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The Pages screen will show the exact live URL.

## Safety
This repository is documentation only. Never publish credentials, passwords, private keys, real user data, or screenshots that reveal secrets. Do not expose DC01/WS01 or Active Directory services to the public internet. Keep the lab on a private host-only network.
