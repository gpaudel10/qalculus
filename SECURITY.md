# Security policy

Security reports are welcome. Qalculus Labs is still under development, and a
careful report can help us fix a problem before it grows with the project.

## What this repository contains

This is a public planning and documentation repository. It should contain only
material that has been approved for public release.

It must never contain:

- passwords, access tokens, private keys, or product credentials;
- private source code or deployment configuration;
- customer, production, or identifiable personal data;
- unpublished research or product-sensitive methods;
- private addresses, hostnames, or network details; or
- unredacted internal job, user, application, or container identifiers.

If you find any of these here, please report it privately and do not copy or
redistribute it.

## Reporting a security issue

Email [paudelg09@gmail.com](mailto:paudelg09@gmail.com) with the subject
`Security report for Qalculus Labs`.

Please include:

- what you found and where you found it;
- the likely impact;
- safe steps we can use to reproduce it; and
- a way to contact you if we need more detail.

Please do not include secrets or personal data in the report unless they are
strictly necessary. If sensitive evidence is involved, describe it first so we
can agree on a safer way to receive it.

## Safe research expectations

Please do not:

- access, change, or delete data that is not yours;
- disrupt a service or test availability through denial-of-service activity;
- use social engineering, credential stuffing, or automated account abuse;
- move beyond the minimum access needed to demonstrate an issue; or
- publish an unresolved vulnerability before we have had a reasonable chance
  to investigate and respond.

We do not currently operate a bug-bounty programme and cannot promise payment.

## Product security direction

The private product is being designed around a few durable principles:

- collect and expose as little sensitive information as possible;
- keep secrets outside source code and public artifacts;
- separate public information surfaces from private product environments;
- limit access by role and deployment need;
- make retention, deletion, and audit expectations explicit; and
- review the security boundary for each deployment rather than relying on one
  universal claim.

This is the direction of the work, not an independent assurance statement.
Qalculus Labs does not currently claim SOC 2, ISO 27001, regulatory approval,
or an independent penetration test.
