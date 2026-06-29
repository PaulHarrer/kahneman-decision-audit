# Kahneman Decision Audit

A Claude skill that audits websites, landing pages, pricing models, sales scripts, and business ideas through the lens of Daniel Kahneman's behavioral economics — then rewrites them to match how people actually decide.

## What it does

Give it a pricing page, homepage, offer, or raw idea. It scores the asset against seven of Kahneman's decision-making principles, flags where each is missing or backfiring, and returns concrete rewrites — not vague advice.

## The seven principles

1. **Anchoring** — the first number sets the frame
2. **Loss aversion** — losing hurts ~2× more than gaining feels good
3. **Framing effect** — same fact, different frame, different choice
4. **Endowment effect** — people value what already feels theirs
5. **Cognitive ease** — familiar and easy reads as true and safe
6. **Peak-end rule** — judged by the peak and the ending
7. **Halo effect** — one strong impression colors the rest

## Output

- **Overall score out of 70** (10 points per principle)
- ✅ / ⚠️ / ❌ status per principle
- Specific before → after rewrites
- Top 3 ranked, highest-leverage changes

## Install

Download `kahneman-decision-audit.skill` and add it via your Claude skills settings.

## Triggers

Fires on prompts like "review my pricing," "improve my landing page," "why isn't this converting," or "critique my business idea" — no need to mention Kahneman by name.