---
name: brand-brief-builder
description: Convert raw brand website text into a structured BD-ready brand intelligence brief for cold-start outreach.
---

# Brand Brief Builder

## Purpose

Transform unstructured brand information into a structured intelligence brief that supports personalized BD outreach.

This skill is designed specifically for cold outbound ecommerce brand partnerships.

---

## Inputs

- Brand name
- Website text OR About section OR short brand description
- Optional: target contact role

---

## Outputs

Structured Brand Brief:

- brand_positioning (Luxury / Premium / Mid-Market / Mass / Value / Unknown)
- core_products
- pricing_tier
- target_customer
- current_channels (DTC / Wholesale / Marketplace / Unknown)
- brand_signals (keywords, tone indicators, differentiators)
- personalization_hooks (2 lines usable in outreach)
- uncertainties (missing or unclear information)

---

## Step-by-Step Behavior

1. Extract only factual information from the provided text.
2. Identify positioning signals (materials, tone, heritage, pricing language).
3. Classify pricing tier if possible; otherwise mark "Unknown".
4. Identify customer segment from language and product focus.
5. Separate facts from assumptions.
6. Generate 2 concise personalization hooks grounded in the input.
7. List uncertainties clearly instead of guessing.

---

## Constraints

- Do NOT invent revenue, partnerships, or performance metrics.
- If information is missing, explicitly state "Unknown".
- Hypotheses must be clearly labeled.
- Do not generalize beyond provided input.

---

## Failure Modes

- Over-assuming positioning from weak signals
- Generating generic hooks
- Hallucinating brand scale or channel presence

If input is too short, return a structured brief with clear "insufficient data" markers.

---

## Example Usage

Input:
Brand: APM Monaco
Text: Contemporary silver jewelry inspired by Monaco lifestyle.

Output:
brand_positioning: Premium
core_products: Silver jewelry
pricing_tier: Mid to Premium
target_customer: Style-conscious adults
current_channels: Unknown
brand_signals: Contemporary, lifestyle-driven
personalization_hooks:
- Noticed your Monaco-inspired contemporary positioning.
- Your silver-focused collections align well with creator-driven discovery.
uncertainties:
- Channel distribution unknown
- Pricing range unclear
