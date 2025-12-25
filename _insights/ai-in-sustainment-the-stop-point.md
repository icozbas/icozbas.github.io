---
layout: article
title: "AI in Sustainment"
hero_highlight: "The Stop Point"
subtitle: "Bounded Automation in ILS/IPS"
description: "Are Integrated Logistics Support (ILS) and Integrated Product Support (IPS) just another passenger on the AI hype train? An engineering view of bounded automation."
date: 2025-12-24
last_modified_at: 2025-12-24
status: ACTIVE
proof: "AI can compress complexity and surface risk, but it must stop before it triggers an irreversible readiness decision without provenance."
tags: [IPS, ILS, Sustainment AI, Decision Support, Auditability, Uncertainty, Intermittent Demand, S-Series]

# --- SEO & META DATA ---
keywords: [IPS, ILS, Sustainment AI, Bounded Automation, Audit Trails, Decision Support, Readiness, Intermittent Demand, S-Series]
seo_title: "AI in Sustainment: The Stop Point | Bounded Automation in ILS/IPS | Izzet Can Ozbas"
seo_description: "Bounded automation in sustainment: what AI can do for IPS, where it must stop, and why audit trails define readiness grade decision support."
og_title: "AI in Sustainment: The Stop Point"
og_description: "Bounded automation in sustainment: what AI can do for IPS, where it must stop, and why audit trails define readiness grade decision support."
og_type: article

# --- REDIRECTION ---
redirect_from:
  - /insights/ai-in-sustainment-the-stop-point/
---

There is a massive AI train speeding through defense sustainment right now. Every conference has a GenAI panel. Every whitepaper has an LLM section. Every tender promises “predictive” everything.

So the question becomes unavoidable: **Are ILS and IPS on this train too?**

My answer is uncomfortable because I sit on both sides. I build models. I care about data. I want better decisions. But I also know the exact station where I need to get off.

Not because AI is useless, but because sustainment is not a playground. In this domain, the failure mode is not “a funny chatbot mistake”. The failure mode is readiness risk.

And readiness does not tolerate ambiguity without accountability.

## The IPS data paradox

The shift from Integrated Logistics Support (ILS) to Integrated Product Support (IPS) is real and it is data-driven. We are moving away from static PDFs and toward structured digital product support ecosystems.

S-Series outputs and related data flows can create a dangerous illusion:

> “We finally have enough data. Just feed it into a neural network and let it run the supply chain.”

This is where many AI narratives quietly break.

In sustainment, “more data” does not automatically mean “more truth”. What it often means is:

- More fields that look precise but encode assumptions
- More records that are consistent in format but inconsistent in meaning
- More text that is operationally important but linguistically messy
- More gaps that only appear when you model tail risk

Compliance produces data. Readiness needs decisions. Those are not the same thing.

## Why “hallucination” is not a joke here

In many civilian settings, a black box optimizer can be tolerated. If it fails, the cost is usually bounded: a late delivery, a suboptimal route, a minor SLA penalty.

In defense sustainment, the cost is not bounded in the same way. A wrong recommendation can cascade:

- An unplanned AOG event
- Cannibalization becoming policy instead of exception
- False confidence in stock posture
- A maintenance plan that looks optimal on paper but collapses under tempo or lead time shocks

The core problem is not “AI makes mistakes”. Humans make mistakes too.

The core problem is: **AI can create confidence without provenance.** And confidence without provenance is operational debt.

That is the heart of the stop point.

## The stop point protocol

My approach is not blind automation. It is **bounded automation**: AI can process signal, compress complexity, and surface risk, but it must stop before it triggers an irreversible action.

If you want a simple mental model:

- Automation is allowed to accelerate analysis.
- Automation is not allowed to finalize accountability.

Here is the protocol.

### 1) AI can detect intermittent demand structure better than humans

Intermittent demand is not “rare demand”. It is often a mix of sparsity, bursts, and long quiet periods. Humans are pattern-seeking and we overfit stories to thin signals.

AI can help by:

- Classifying demand behavior (lumpy, intermittent, erratic)
- Proposing scenario distributions rather than single point forecasts
- Quantifying uncertainty instead of hiding it inside averages

This is not about “prediction magic”. It is about identifying which parts of the portfolio require probability first planning.

### 2) AI can clean and standardize messy support data

A large portion of sustainment data is not model ready. It is free text, inconsistent naming, partial fields, or operational shorthand.

AI is genuinely useful here:

- NLP-assisted normalization of maintenance narratives
- Entity extraction for part references, symptoms, failure modes
- Mapping inconsistent descriptions into analytics ready categories

This is the data bridge work. It turns the library into decisions, without pretending the library is the decision.

### 3) AI cannot be the final authority on readiness risk without auditability

This is the station where I get off.

In ILS/IPS, if a model recommends:

- Do not stock this critical spare
- Delay this maintenance action
- Accept this availability risk

Then the decision must be traceable to assumptions, inputs, and sensitivity. Otherwise it is not a decision, it is a bet.

I do not sell opaque black boxes, and I do not claim certainty where uncertainty dominates.

## Black box vs glass box

ILS/IPS does not need a black box. It needs a **glass box**.

A glass box recommendation answers three questions:

1. **What is the decision?**  
   Example: increase buffer stock for a specific SKU, or trigger an engineering review.

2. **What is the uncertainty?**  
   Example: demand is sparse, lead time volatility dominates, failure rates are regime dependent.

3. **What changes the decision?**  
   Example: a tempo increase shifts the risk curve, supplier constraints change the threshold, deployment context alters acceptable exposure.

This is the missing middle: the decision layer between raw data and operational action.

## Where bounded automation becomes practical

If you want to operationalize the stop point, it helps to define boundaries in concrete terms.

**Allowed automation (Decision Support):**

- Risk scoring with confidence bands
- What if scenarios (tempo, lead time shocks, demand bursts)
- Prioritization queues: review these 20 parts first
- Sensitivity reports: if lead time variance doubles, this is the impact
- Data quality flags and anomaly detection

**Stop point triggers (Human accountability required):**

- Stocking changes for mission critical items
- Maintenance deferral recommendations
- Policy changes that affect readiness exposure
- Actions that are hard to reverse under operational tempo

Sustainment outcomes must be defensible. That means reviewable reasoning, explicit assumptions, and sensitivity by design.

## What this means for the AI hype train

So, am I on the AI train?

Yes.

But I am not riding it to full autonomy narratives. I am riding it to a specific station: **decision support under uncertainty**.

Because the product I actually sell is not automation. It is decision confidence.

And confidence only counts when you can explain it, test it, and audit it.

That is the stop point.

If your ILS/IPS AI roadmap cannot answer:

- What the model assumes
- What the uncertainty band is
- What changes the action threshold

Then you do not have decision support. You have a demo.

And demos do not keep fleets ready.
