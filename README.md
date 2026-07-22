# All Site Connect

Static construction-site internet rental website prepared for GitHub Pages.

## Before publishing

1. Open `index.html`.
2. Replace `(000) 000-0000` with your phone number.
3. Replace every instance of `quotes@allsiteconnect.com` with the email address that should receive quote requests.
4. Commit the changes.

## Enable GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`.
6. Click **Save**.

GitHub will publish the site at:

`https://joem-source.github.io/allsiteconnect.com/`

## Connect the GoDaddy domain

In the GitHub repository, open **Settings → Pages** and enter:

`allsiteconnect.com`

Then update the domain's DNS records in GoDaddy using the values GitHub displays. GitHub's current documentation should be followed because DNS targets can change.

## Files

- `index.html` — page content and quote form
- `styles.css` — visual design and mobile layout
- `script.js` — mobile menu and automatic copyright year
- `.nojekyll` — ensures GitHub Pages serves the site as a plain static site
