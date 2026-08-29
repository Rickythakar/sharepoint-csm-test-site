# SharePoint Test Site

A standalone HTML/CSS mock landing-page shell for planning a **Customer Success SharePoint resource hub**. The visual system is intentionally constrained to layouts and components that can be recreated with native SharePoint modern-page web parts.

## Live prototype

[Open the Customer Success Hub mockup](https://rickythakar.github.io/sharepoint-test-site/)

The hosted page is a presentation prototype only. It contains fictional placeholder content and is not connected to company systems or data.

The page demonstrates a polished, low-maintenance information architecture using familiar native SharePoint concepts:

- Page banner and governance details
- Quick Links
- Common SOPs
- New SOPs / What's New
- Recently Updated Files
- General Resources

## SharePoint build map

| Mockup section | Native SharePoint implementation |
| --- | --- |
| Page introduction | Banner and Text web parts in a one-column section |
| Start here | Quick Links web part using Grid layout |
| New to the team | Text and Quick Links web parts in a two-column section |
| Knowledge & dashboards | Quick Links web part using Grid layout |
| Common SOPs | Document Library web part or a saved library view |
| What's new | Highlighted Content web part sorted by recently changed |
| Recently updated files | Document Library or Highlighted Content web part |
| Browse resources | Quick Links web part using Compact layout |

The layout uses ordinary one-column and two-column sections. It does not depend on a Communication-site-only full-width section, custom JavaScript, embedded HTML, or a SharePoint Framework web part.

## Important

This is a planning mockup only. All names, dates, statuses, links, and document details are fictional placeholders. The site is not connected to SharePoint, production systems, or company data.

## View locally

Open `index.html` in a browser, or serve this folder with any basic static-file server.

## Files

- `index.html` — page structure and placeholder content
- `styles.css` — responsive visual styling

No build step, framework, or external dependency is required.
