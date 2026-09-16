# The Cleaning Queen — making it theirs

    ~/.atlas/bin/client publish the-cleaning-queen

## The enquiry form — READ THIS FIRST

Posts to **FormSubmit** at `enocherdner@gmail.com`. **Activated and tested end to end
on 2026-09-16** — a real submission from the live page arrived in the inbox with every
field. Working.

**When they become a client**, change the address in the `<form action=...>` line
to `doris.and.adrian.llc@gmail.com`, change the `_next` value if the domain
changes, and restore the reassurance line under the button to
"Goes straight to them — nobody else." (It is currently "Sent straight through —
no account, no sign-up", which is true while the form comes to Enoch.)

## Insights — the thing the retainer is actually sold on

The page counts **Call tapped**, **Email tapped** and **Enquiry sent**. Pageviews
are vanity. `track()` feeds Umami, Plausible or GA — whichever tag is installed.

### Correction, 2026-09-16: Cloudflare will not do this job

The earlier note here said to use Cloudflare Web Analytics. It is free and
cookieless, but **its basic beacon only records pageviews — it cannot track
tap-to-call.** It cannot produce "eleven people tapped your number", which is the
whole sentence the retainer is sold on. Do not rely on it for this.

### Who can see the numbers — checked against the vendors' own docs

| Option | Private to the owner? | Client needs an account? | Cost |
|---|---|---|---|
| Umami free **share link** | **No** — unguessable, but anyone with the URL sees it | No | $0 |
| Umami **Teams**, View Only role | Yes, a real login | Yes | **Pro plan, not free** |
| **Plausible + password-protected share link** | **Yes** | **No** | $9/mo |
| **No dashboard — Enoch reports the numbers** | Yes | No | $0 |

Sources: docs.umami.is/docs/cloud/teams ("Teams is available starting at the Pro
plan"), plausible.io/docs/shared-links (shared links support password protection).

### What to actually do

**Now, while nobody is paying:** install Umami free and **publish no share link.**
Data collects, Enoch can see it, the public cannot, and nothing is promised that
cannot be delivered.

**When a client is on a retainer and wants to self-serve:** Plausible at $9/mo,
shared link with a password. The client needs no account and the public sees
nothing. One retainer covers it many times over.

**Do not hand out a naked Umami share link for a client's business.** It is a
public URL for someone else's commercial data.

### The part worth remembering

A dashboard the owner opens twice and forgets does not renew a retainer. **A text
from Enoch saying "eleven people tapped your number last month" does.** RETAINER.md
already promises "a short note at the end of each month" — that note *is* the
product, and the dashboard is a bonus for the ones who ask.

## Switching the counting on

1. cloud.umami.is → sign up → Add website
2. Settings → Websites → Edit → Tracking code → copy the one-line tag
3. Paste it in `index.html` directly under `ANALYTICS TAG GOES HERE`
4. `client publish the-cleaning-queen`, then tap the phone number and confirm the
   event appears in Umami

Free tier: 10k events/month, 3 websites. Cookieless, so no cookie banner.
