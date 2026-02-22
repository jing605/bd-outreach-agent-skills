# BD Outreach Agent Skills Pack  
MSIS 549 – Agentic AI for Business Applications  

## Problem Statement

Cold outbound BD outreach to ecommerce brands is repetitive, manual, and often inconsistent. 

The process typically requires:
- Reading brand website content
- Forming a platform-fit hypothesis
- Crafting a personalized outreach email
- Avoiding generic language and hallucinated claims

This skills pack modularizes that workflow into reusable components.

---

## System Overview

This agentic workflow consists of three structured skills:

1. **Brand Brief Builder**  
   Converts unstructured brand text into a structured intelligence brief.

2. **Growth Angle Generator**  
   Translates the brand brief into a TikTok Shop-specific growth thesis.

3. **Outreach Composer**  
   Generates a send-ready cold BD email grounded in brand-specific reasoning.

Together, these skills simulate a real BD reasoning pipeline:
Research → Strategy → Execution.

---

## Intended User

TikTok Shop Category BD / Operations professional performing cold outbound outreach.

---

## Success Criteria

The system succeeds if it produces:

- A personalized outreach email under 220 words
- At least 2 brand-specific hooks
- A clear platform-fit thesis
- No hallucinated metrics or fabricated claims
- A low-friction CTA

---

## Example Workflow

Step 1: Input brand website text into Brand Brief Builder.  
Step 2: Pass structured output into Growth Angle Generator.  
Step 3: Pass strategy output into Outreach Composer.  
Step 4: Review and send.

---

## Limitations

- Dependent on quality of brand input text.
- Does not verify factual accuracy unless paired with external research tools.
- May default to generic strategy if brand positioning is unclear.

---

## Future Improvements

- Add MCP-enabled web verification tool.
- Add quality scoring layer for regression testing.
- Add brand segmentation logic for luxury vs mass differentiation.
