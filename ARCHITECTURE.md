# FlorSal Group Enterprise Architecture

## 1. Business architecture

FlorSal Group is organized into six strategic business sectors:

- FlorSal Academy
- FlorSal Tech
- FlorSal Consulting
- FlorSal Transport
- FlorSal Leather
- FlorSal Naturals

Each sector owns its programs, products, services, clients and roadmap.

## 2. Application architecture

### FlorSal Academy

Programs are organized inside one educational platform. Trading is the first program, followed by accounting, finance, analytics, artificial intelligence, programming, languages and research.

### FlorSal Tech

FlorSal Tech contains:

- Products: Financial Control, FlorFlow, ERP, FlorSal OS and future shared platforms.
- Client solutions: MSD, ADP, Caldwell and other customer-specific systems.
- Shared services: authentication, notifications, reporting, audit, document management and reusable UI components.

### Other sectors

Consulting, Transport, Leather and Naturals will receive dedicated applications only when a validated business need exists.

## 3. Data architecture

- Each product owns its operational data.
- Shared identity data should be centralized only when technically and legally justified.
- Client data must remain separated from FlorSal corporate data.
- Financial, payroll and personal information requires restricted access and audit trails.
- Source repositories must never contain production data.

## 4. Technology architecture

Preferred low-cost stack principles:

- Open-source frameworks and databases.
- Static hosting or free tiers for public websites.
- Local servers when appropriate for internal systems.
- GitHub for source control, issues and documentation.
- Automation only when it reduces recurring manual work.

## 5. Domain architecture

Planned domains:

- `florsal.com` — corporate portal.
- `academy.florsal.com` — educational platform.
- `tech.florsal.com` — technology sector.
- `consulting.florsal.com` — consulting sector.
- `transport.florsal.com` — transport sector.
- `leather.florsal.com` — leather sector.
- `naturals.florsal.com` — natural products sector.

Future shared services may use `docs.florsal.com`, `status.florsal.com`, `api.florsal.com` or `auth.florsal.com` only when justified.

## 6. GitHub architecture

```text
Corp-Florsal/
├── .github
├── florsal-academy
├── florsal-tech
├── florsal-consulting
├── florsal-transport
├── florsal-leather
├── florsal-naturals
└── florsal-brand
```

Product and client repositories may remain separate when independent deployment, security, licensing or lifecycle management requires it.

## 7. Architectural principles

1. Business ownership before technical implementation.
2. Reuse before duplication.
3. Security and privacy by design.
4. Low recurring cost.
5. Clear separation between products and client solutions.
6. Documentation before transfer or major restructuring.
7. Incremental growth rather than premature complexity.
