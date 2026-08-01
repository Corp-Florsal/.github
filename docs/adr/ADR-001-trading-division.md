# ADR-001: FlorSal Trading as a business division

- **Status:** Accepted
- **Decision owner:** Founder and CEO of FlorSal Group
- **Date:** 2026-08-01

## Context

FlorSal Group will both execute real trading operations and develop educational content about trading. These activities require separate ownership, goals and controls.

## Decision

FlorSal Trading is established as a business division of FlorSal Group.

Its purpose is to:

- Execute real trading operations.
- Manage the trading budget and capital.
- Control gains, losses and cash movements.
- Apply risk limits and position-sizing rules.
- Maintain trading journals, playbooks and performance analytics.
- Manage funded-account evaluations and active accounts.
- Document validated operating experience.

FlorSal Trading is not an educational program and does not manage students or certifications.

## Relationship with FlorSal Academy

FlorSal Academy owns the educational platform. Its Trading program converts validated knowledge into lessons, exercises, assessments and learning materials.

## Relationship with FlorSal Tech

FlorSal Tech develops and maintains reusable software products used by FlorSal Trading and other divisions, including Financial Control, ERP, workflow and analytics tools.

## Repository consequences

- Create `Corp-Florsal/florsal-trading` for the operating division.
- Rename `Corp-Florsal/florsal-trading-academy` to `Corp-Florsal/florsal-academy`.
- Keep the Academy Trading program inside `florsal-academy`.
- Do not merge real trading records with educational student data.
- Keep sensitive trading and account information private.
