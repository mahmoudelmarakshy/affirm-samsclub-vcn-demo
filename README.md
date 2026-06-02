# Sam's Club × Affirm — Direct Checkout Virtual Card (VCN) Integration Demo

An interactive, **simulation-only** walkthrough of the Affirm Direct Checkout + Read Card
(Virtual Card Number) integration, framed for a Sam's Club storefront.

> **This is a static demo.** It makes **no live API calls**, uses **no proxy**, and contains
> **no credentials**. Every "API" response is canned, illustrative test data so the end-to-end
> flow can be shown anywhere as a plain web page.

## What it shows

- A Sam's Club storefront (member view) with a cart and an Affirm "as low as $/mo" CTA.
- The full sequence of operations between the storefront frontend/backend, Affirm, Walmart's
  Token Security Service (TSS), and the payment processor.
- A live "Backend activity" log with representative Direct Checkout and Read Card request/response
  payloads.
- A self-contained mock Affirm checkout (happy path = loan confirmed; cancel path = member backs out).
- The encrypted VCN (JWE) → TSS decrypt → processor authorization flow.

## Running locally

Just open `index.html` in any browser — no server required.

---

Built with Cursor (AI coding agent).
