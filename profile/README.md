<img src="https://raw.githubusercontent.com/deal-ops/.github/main/assets/deal-ops-logo-square.png" width="64" height="64" alt="Deal Ops logo" />

# Deal Ops

Open-source tools for SPV and syndicate deal operations: the work between "investors committed" and "money paid out", done to the penny and checked at every step.

[Website](https://deal-ops-toolkit-site.vercel.app) · [Toolkit](https://deal-ops-toolkit-site.vercel.app/toolkit/) · [Inbox](https://deal-ops-toolkit-site.vercel.app/inbox/)

## Projects

| Project | What it does | Status |
|---|---|---|
| [**Deal Ops Toolkit**](https://github.com/deal-ops/deal-ops-toolkit) | A browser tool for SPV deal operations: match bank receipts to commitments, work out the closing allocation, and split exit proceeds with carry and a hurdle. Deal data stays in your browser. | Working prototype · [open the app](https://deal-ops-toolkit.vercel.app) · [website](https://deal-ops-toolkit-site.vercel.app/toolkit/) |
| [**Deal Ops Inbox**](https://github.com/deal-ops/deal-ops-inbox) | A self-hosted, read-only email agent for investment-operations inboxes: it classifies each email, extracts the key facts, links it to your directory, flags risk and drafts a reply from a fixed template for a person to review, copy and send. It never sends email. | v0.1.1 · [online demo](https://deal-ops-toolkit-site.vercel.app/inbox/demo/) · [website](https://deal-ops-toolkit-site.vercel.app/inbox/) · [release notes](https://github.com/deal-ops/deal-ops-inbox/releases/tag/v0.1.1) |

More components will be listed here when they are released.

## Principles

- **Money is exact.** Integer minor units and exact arithmetic; no floating point.
- **Every number explains itself.** Each result shows where it came from, and every calculation checks itself.
- **People decide.** Tools suggest; a person confirms anything that moves money or changes a record.
- **Independent checks.** Key calculations are cross-checked against a second, separately written implementation.

Not affiliated with any platform. Sample data is fictional.
