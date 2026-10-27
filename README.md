# Ledgerline – SaaS analytics dashboard

A single-file subscription metrics dashboard. No build step, no dependencies.

## What it shows

- ARR, active customers, revenue per customer, monthly revenue churn, net revenue retention
- MRR trend with hover details
- MRR movement: new, expansion, contraction and churn
- Revenue by plan
- Cohort retention table
- 3, 6 and 12 month range switch, with light and dark mode

## Run it

Open `index.html` in a browser.

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Use your own data

The sample data is defined at the top of the `<script>` block in `index.html`:

| Variable | Meaning |
| --- | --- |
| `NEW`, `EXP`, `CON`, `CHU` | Monthly new, expansion, contraction and churned revenue |
| `CN`, `CC` | Monthly new and churned customers |
| `PLANS` | Plan share of MRR |
| `COH` | Cohort retention percentages |

Replace these arrays and the charts update automatically.

## License

MIT
