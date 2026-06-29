# TOC Landing Page

A lead-generation landing page for the free Shopify inventory ordering tool.

## Overview

This is a simple, static HTML landing page that collects leads via a form. When visitors sign up, they receive:
- A copy of the inventory ranking spreadsheet
- A 5-minute walkthrough video (Loom)
- Option to book a free 30-minute strategy call

## How it works

1. Visitor fills out the form (name, email, website, role)
2. Form data posts to a Google Apps Script backend
3. Visitor is added to a lead sheet and sent an auto-email
4. They receive a copy of the template and walkthrough link

## Deployment

This site is deployed to GitHub Pages at **https://go.doctordigits.com** via a custom domain (CNAME).

## Files

- `index.html` — The landing page (HTML + CSS + JavaScript)
- `kyle-kent.png` — Profile photo
- `CNAME` — Custom domain configuration for GitHub Pages
- `.gitignore` — Git ignore rules

## Local development

Simply open `index.html` in a browser. No build step, no dependencies.

---

Built with plain HTML, CSS, and JavaScript. Form backend via Google Apps Script.
