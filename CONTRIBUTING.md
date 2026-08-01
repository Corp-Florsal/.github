# Contributing to FlorSal Group

Thank you for contributing to a FlorSal Group project.

## Before you start

1. Confirm that the work belongs to the correct business sector.
2. Check whether an issue already exists.
3. Never commit credentials, personal data, client data or production secrets.
4. Use a clear branch name and keep the change focused.

## Branch naming

- `feature/<short-description>`
- `fix/<short-description>`
- `docs/<short-description>`
- `refactor/<short-description>`
- `chore/<short-description>`

## Commit messages

Use concise conventional-style messages:

- `feat: add risk calculator`
- `fix: correct invoice status transition`
- `docs: update installation guide`
- `refactor: simplify authentication service`
- `chore: update dependencies`

## Pull requests

A pull request should include:

- Purpose of the change.
- Scope and affected modules.
- Testing performed.
- Screenshots for visual changes.
- Security or privacy impact.
- Related issue, when applicable.

## Quality requirements

- Code must be readable and documented where necessary.
- New functionality should include tests when practical.
- Existing behavior must not be broken without explanation.
- User-facing text should follow the language and branding standards of the product.
- Client-specific logic must not be placed in reusable FlorSal products without clear separation.

## Review

At least one maintainer review is recommended before merging important changes. Security-sensitive, financial or client-data changes require explicit review.
