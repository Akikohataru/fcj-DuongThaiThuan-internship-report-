---
title: "Event 1"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Event Report: FCAJ Community Day – May 23, 2026

## Quick Facts

- **Event:** FCAJ Community Day – May 2026
- **Host:** First Cloud Journey (FCAJ)
- **When:** Saturday, May 23, 2026
- **Where:** Ho Chi Minh City (in-person)
- **Format:** Tech talks + hands-on workshop
- **Theme:** Generative AI in the enterprise

## Why I Joined

This was the very first community event I attended as part of my internship. I went in with one question: *how are Vietnamese engineers actually using AI and AWS in production?* I expected slides. I left with hands-on experience building parts of a real AI system.

## Program Highlights

Instead of a flat schedule, the day was structured around **three threads** running in parallel:

### Thread 1 — The Knowledge Layer

- Tinh Truong (GoTymeX): the realities of running LLMs inside a fintech product
- Anh Pham (G-AsiaPacific): where Amazon Q fits in a typical SDLC
- Thinh Nguyen (FCAJ): the thinking behind MCP and why context matters more than model size

### Thread 2 — The Hackathon Reality Check

The UTMorpho trio from VIB (Uyen Le, Thao Nguyen, Mai Nguyen) walked us through their 18-hour build. The lesson wasn't the technology — it was **how they split the work, cut scope, and used AI as a pair-programmer under time pressure**.

### Thread 3 — The Workshop Floor

Duc Dao (Cloud Kinetics) and Vy Lam (VPBank) ran us through five guided exercises that built one coherent system, end-to-end:

1. Cognito + JWT authentication
2. Bedrock Guardrails for safe outputs
3. IAM Permission Boundaries (least privilege)
4. MCP server integration
5. Terraform stack for reproducible deploys

## The One Idea I Keep Coming Back To

> A guardrail is not a filter you bolt on at the end. It is a design decision you make before the first prompt is written.

This sentence from Duc Dao reframed how I think about AI safety. Permission boundaries, prompt design, and content filters are not three separate concerns — they are **one concern viewed at three layers**.

## What This Event Changed For Me

Before this event, AI was a thing I read about. After this event, I have a mental map of how the pieces connect, and a checklist I now use whenever I touch an AI feature:

- Who is allowed to call this?
- What is allowed to leave this endpoint?
- What context does the model actually need?
- Can I reproduce this deployment from a single `terraform apply`?

## Photos

![Attending FCAJ Community Day with fellow participants]({{< baseurl >}}images/4-EventParticipated/event1.jpg)

## Closing Thought

This was the kickoff of my AI exposure outside of coursework. It set the tone for everything that followed in my internship — every blog I wrote, every architecture decision in the SmartMenu project, every time I touched Bedrock or MCP, traces back to ideas I first heard in that room on May 23.
