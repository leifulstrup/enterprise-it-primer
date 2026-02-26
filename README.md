# Enterprise IT Fundamentals Primer for MBA Students

A comprehensive reference primer covering enterprise IT concepts for first-year MBA students at AU Kogod School of Business. Built as a companion to ITEC-617 "Information and Technology."

## What This Covers

Topics that MBA graduates need to understand but cannot be covered in depth during the half-semester course:

- **IT Governance** — Frameworks (COBIT, ITIL), C-suite roles, IT-business alignment, budgeting
- **Enterprise Technology** — Make vs. buy, cloud computing, data centers, enterprise architecture, ERP/CRM/SCM
- **Risk & Security** — Shadow IT, cybersecurity governance, data governance
- **Digital Transformation** — Frameworks, AI strategy, business process management
- **IT Management** — Vendor management, project management, PMO
- **Reference** — Glossary, framework quick-reference cards, case studies, further reading

## Live Site

**[https://leifulstrup.github.io/enterprise-it-primer/](https://leifulstrup.github.io/enterprise-it-primer/)**

## Running Locally

```bash
# Install dependencies
uv sync

# Start dev server (auto-reloads on changes)
uv run mkdocs serve

# Build the site
uv run mkdocs build --strict
```

## Running Tests

```bash
# Install test dependencies
uv add --dev pytest playwright
uv run playwright install chromium

# Run tests
uv run pytest tests/ -v
```

## Project Structure

```
├── docs/                    # All site content (Markdown)
│   ├── index.md            # Landing page
│   ├── governance/         # IT governance topics
│   ├── technology/         # Enterprise technology topics
│   ├── risk-security/      # Risk and security topics
│   ├── transformation/     # Digital transformation topics
│   ├── management/         # IT management topics
│   └── reference/          # Glossary, case studies, further reading
├── includes/               # Shared content (abbreviation tooltips)
├── mkdocs.yml              # Site configuration
├── tests/                  # Build and browser tests
└── .github/workflows/      # GitHub Actions deployment
```

## Technology

- [MkDocs](https://www.mkdocs.org/) with [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme
- Deployed via GitHub Pages with GitHub Actions
- Managed with `uv` (Python package manager)

## Author

Professor Leif Ulstrup — AU Kogod School of Business
