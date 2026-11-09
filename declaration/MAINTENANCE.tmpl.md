# {{PROJECT}} Maintenance

> Template: Open Commons Maintenance (OCM) 1.0. Fill in the placeholders,
> keep the guarantees and the Active Usage Equivalents rules unchanged.
> Your `LICENSE` file stays exactly as it is. This file is not a license.

{{PROJECT}} is open source under {{LICENSE}}. Every feature is available to
everyone, always. This file describes how the ongoing maintenance of the
project is funded, following the
[Open Commons Maintenance (OCM)](https://github.com/Jersyfi/open-commons-maintenance)
model.

## Principles

1. **Same software for everyone.** No paid editions, no feature gates,
   no "community" branding on free users.
2. **Payment is voluntary.** We cannot and will not enforce payment.
   There are no license keys, no phone-home, no lockouts.
3. **Contribution follows actual use.** Dormant installations pay nothing.
   Those who rely on {{PROJECT}} commercially carry a larger share.

## How use is measured: Active Usage Equivalents (AUE)

Use is measured locally, in one unit for humans and machines alike:

- A **human account** active on at least 3 days in a month counts as 1 AUE.
- An **agent or integration credential** (API key, service token, client ID)
  active on at least 3 days in a month counts as 1 AUE, regardless of the
  number of requests within the fair-use band below.
- **Fair-use band:** installations with more than {{FAIR_USE_1}} API requests
  per month count as at least {{FAIR_USE_1_AUE}} AUE; more than
  {{FAIR_USE_2}} as at least {{FAIR_USE_2_AUE}} AUE.
- **Dormant rule:** installations with at most 12 active days per year
  pay nothing.

Nothing is transmitted automatically. You can export a signed attestation
containing only the period and your tier (useful for CRA/NIS2/ISO 27001
compliance evidence).

## Suggested annual contribution

| Tier | AUE | Reference | Community ({{COMMUNITY_PCT}}) | Start ({{START_PCT}}) |
| --- | --- | --- | --- | --- |
| Dormant | ≤ 12 active days/year | 0 | 0 | 0 |
{{TIER_TABLE}}

**Classes (self-assessed, no proof required, same software for all):**

- **Free** – anyone who cannot or does not want to pay.
- **Community ({{COMMUNITY_PCT}})** – individuals, families, clubs, schools,
  research.
- **Start ({{START_PCT}})** – solo self-employed, micro businesses, new
  projects.
- **Reference (100%)** – all other commercial use, including offerings built
  on the {{PROJECT}} API with AI agents or automation.

Everyone receives the same releases, documentation, and community support.

## Guarantees

1. No feature gate, ever.
2. No rug-pull: this project will never move to a non-OSI license
   (contributions are accepted via DCO, without copyright transfer).
3. No lockout on non-payment.
4. No data leaves your server for billing purposes.

## Transparency

Once a year we publish a short maintenance report: releases, fixed
vulnerabilities, response times, and a funding band (<50%, 50–99%, ≥100% of
the stated maintenance budget). At least {{FAIR_SHARE_PCT}}% of maintenance
contributions flow into maintenance and development work, including
maintainer compensation.

## Assurance (optional, on request)

Organizations needing SLAs, LTS commitments, guaranteed response times,
SBOM attestations, or audit support can request an assurance contract.
Contact: {{CONTACT}}.

## How to contribute money

{{PAYMENT_LINKS}}
