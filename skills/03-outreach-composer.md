---
name: outreach-composer
description: Generate a personalized, send-ready BD outreach email based on brand brief and growth strategy outputs.
---

# Outreach Composer

## Purpose

Generate a high-quality, cold outbound BD outreach email that is:
- Brand-specific
- Strategically positioned
- Credible and non-generic
- Ready to send with minimal editing

This skill integrates outputs from:
- brand-brief-builder
- growth-angle-generator

---

## Inputs

- Brand brief (structured output from Skill 1)
- Growth strategy output (Skill 2)
- Contact name (optional)
- Contact role
- Sender identity (e.g., TikTok Shop BD / Category Ops)
- CTA preference (Intro call / Share deck / Ask referral)

---

## Outputs

- subject_lines (3 options)
- email_body (150–220 words)
- CTA_line
- personalization_elements_used (list of hooks used)

---

## Step-by-Step Behavior

1. Open with one brand-specific hook from the brand brief.
2. Introduce TikTok Shop positioning using the growth thesis.
3. Provide 2 value bullets aligned to the recommended growth model.
4. Anticipate one possible concern and subtly address it.
5. End with a low-friction CTA.
6. Ensure tone matches contact seniority:
   - VP/CMO: strategic framing
   - Manager: execution & experimentation

---

## Constraints

- Do not fabricate metrics or platform performance numbers.
- Do not invent partnerships or brand details.
- Avoid generic praise like "I love your brand."
- Do not overuse discount-driven positioning for premium brands.
- Keep email under 220 words.
- Avoid overly aggressive tone.

---

## Failure Modes

- Email sounds templated or generic.
- Personalization hook is weak or vague.
- CTA is unclear.
- Over-promising results.

If brand data is insufficient, clearly note assumptions in output.
