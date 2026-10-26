# Document Approval: Security Awareness Landing Page

A static page shown to employees after they take part in an authorized
phishing simulation. It explains what happened, reassures them that no
credentials were collected, and lists the habits that help them spot real
phishing attempts.

## What it is for

Security teams run simulated phishing emails to check how well staff spot
suspicious messages and to teach better habits. When someone clicks through
a simulated email, they land on this page instead of a real request, so they
learn what happened right away.

## What the page does

- Tells the reader that the exercise was an authorized security-awareness test.
- States clearly that no passwords or other credentials are requested or stored.
- Gives a short checklist for next time:
  - Verify the sender's email address.
  - Check whether you expected the document.
  - Confirm unusual approval requests through a separate channel.
  - Inspect a link's destination before opening it.
  - Report suspicious emails to the security team.

The page is a single HTML file with inline styles. It has no forms, no
scripts, and no external requests.

## Authorized use only

This page should be used only as part of a security-awareness program run by
the organization that owns the employees being tested. Do not use it to
trick people outside an approved exercise, to collect information, or to
impersonate any real person or organization.

## Customizing

- Edit `index.html` to match your organization's name, support contact, and
  reporting process. Keep the no-credentials statement accurate for your test.
- Keep the page free of forms and scripts that request data. If an exercise
  ever needs data collection, it needs a separate review first.

## Files

- `index.html`: the landing page
- `README.md`: this file
