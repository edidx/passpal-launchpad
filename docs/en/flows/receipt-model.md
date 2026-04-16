# Receipt Model

A PassPal Receipt is the decision artifact returned by the flow.

## Typical fields

A receipt may include:

- receipt ID
- action
- requested inputs
- received inputs
- decision summary
- outcome
- freshness or expiry
- next action

## Why the receipt matters

The goal is to produce something more useful than a simple "verified / not verified" result.

The receipt helps a relying party understand:
- what was requested
- what was received
- what outcome was reached
- what should happen next
