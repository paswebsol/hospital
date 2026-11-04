HMS CLIENT APP — GITHUB PAGES DEPLOYMENT

This folder is the CLIENT APP only. It does not contain the private licence issuer.

DEPLOY
1. Create a new GitHub repository (Public if using free GitHub Pages).
2. Upload every file INSIDE this client-site folder to the repository root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish, then open the HTTPS Pages address.

CLIENT ACTIVATION
1. The client opens the published app URL.
2. The activation screen displays a Device ID.
3. The client sends that Device ID to the software owner.
4. The software owner generates a key using the separate private issuer.
5. The client pastes the key and activates.

IMPORTANT
- Do NOT upload private-issuer/issuer.html into the public client repository.
- Keep the issuer file private and use it separately.
- A licence is tied to the browser/device installation. Clearing browser storage or changing browser/device may require reactivation.
- This browser-only licensing is basic deterrence, not tamper-proof. Strong protection requires a server-side licensing service.
- Use the HTTPS GitHub Pages URL; installation and secure device ID generation require a secure context.
