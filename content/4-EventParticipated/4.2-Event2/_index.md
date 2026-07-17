---
title: "Event 2"
date: 2026-06-27
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Event Report: FCAJ Community Day – June 27, 2026

## Quick Facts

- **Event:** FCAJ Community Day – June 2026
- **Host:** First Cloud Journey (FCAJ)
- **When:** Saturday, June 27, 2026
- **Where:** Ho Chi Minh City (in-person)
- **Format:** Tech talks + live product demos
- **Theme:** AI moving from slideware to production

## Why This One Mattered More

The first FCAJ Community Day in May taught me the *vocabulary*. This second one showed me the *bill of materials*. Where the May event leaned on theory and hands-on labs, the June event was built around **four live, unbroken product demonstrations** — Voice AI, AgenticOps, Amazon Q for HR, and an Amazon Q + MCP stack hardened with VPC and IAM controls.

I went in curious. I left with a notebook full of diagrams I had never seen before.

## Four Live Demonstrations, Four Mental Models

### 1. Voice AI — When the model talks back

Trung Vu (Revve AI) brought a voice agent on stage and let it take real calls from the audience. The thing that surprised me was not that it worked — it was **how little of the screen was occupied by the model itself**. Most of the latency budget was spent on speech recognition, intent routing, and tool execution *around* the LLM. The model was the easy part.

### 2. AgenticOps — AI as a teammate, not a tool

Anh Trường and Minh Anh Đặng Cao (Noventiq Vietnam) demoed an E-shop pipeline where a DevOps Agent watched builds, opened tickets, and rolled back failed deploys without a human in the loop. Their point was sharp: the value of AgenticOps is not *replacing* operators — it is **buying back their attention** for the failures that actually matter.

### 3. Amazon Q for HR — Retrieval over reasoning

Bao Phan Kim and Minh Nguyen Nguyen walked through an HR assistant connected to internal policy docs. The most useful thing I took away was the framing: Amazon Q was not *generating* answers, it was **retrieving policy fragments and stitching them with citations**. The recruiter in the demo could see exactly which document each sentence came from.

### 4. Amazon Q + MCP + VPC — A security story disguised as a feature demo

Đức Toàn Nguyễn (AWS Security Builder) closed the day by connecting Amazon Q to an internal MCP server — and then locking the whole thing inside a private VPC. The demo doubled as a security lecture. The lesson: *Amazon Q does not need to be the weakest link in your network.*

## Two Conversations That Stuck

Between sessions, I had two short conversations that shaped how I now plan my next learning steps.

- **Nhat Tran (CloudThinker)** told me about earning his first AWS certification in 2020–2021 — and then doing *nothing* with it for a year while he built the rest of the picture. That sentence reframed my obsession with certificates into something healthier.
- **Nghị Danh Hoàng Hiếu (Renova Cloud)** said the most underrated skill for a cloud engineer today is learning to *say no* to features that look good in a demo but hurt the architecture long-term. I am now writing that on my wall.

## What I Took Back To The SmartMenu Project

- I redrew the SmartMenu architecture with an explicit *context boundary* — a private VPC, an MCP server, and an Amazon Q layer for internal documentation retrieval. Same product, but now with clear trust zones.
- I added a "where does this data come from?" column to our retrieval evaluation table, taken directly from the HR demo.

## Photos

![Group photo at FCAJ Community Day – June 27, 2026]({{< baseurl >}}images/4-EventParticipated/event2.jpg)

![Event hall – presentation by Revve AI]({{< baseurl >}}images/4-EventParticipated/event_2_3.jpg)

## Closing Thought

If the May event gave me the *vocabulary* of enterprise AI, the June event gave me the *checklist*. Every demo followed the same hidden pattern — guardrails, retrievable context, a clear trust boundary, and a human in the loop where it counts. I expect that pattern to keep showing up in everything I build for the rest of this internship.
