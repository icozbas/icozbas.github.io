---
layout: article
title: "AI in Sustainment"
hero_highlight: "The Stop Point"
subtitle: "Why Bounded Automation is the Only Way for ILS/IPS"
description: "Everyone in defense sustainment feels the pressure to adopt AI. Here is the engineering view on bounded automation: what AI can do, where it must stop, and why readiness requires provenance."
date: 2025-12-24
last_modified_at: 2025-12-26
status: ACTIVE
proof: "AI should accelerate analysis, compress complexity, and surface risk, but it must stop before it triggers an irreversible action."
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

Everyone in defense sustainment feels the pressure right now. From conferences to tenders, the message is loud: "Adopt AI or get left behind." It is tempting to jump on the bandwagon, promising predictive maintenance and automated supply chains.

But as engineers working in Integrated Logistics Support (ILS) and Integrated Product Support (IPS), we have to ask the uncomfortable question: **Is this safe?**

I sit on both sides of this argument. I build models, I love data, and I advocate for better decision-making tools. But I also know exactly where the automation must stop. Not because I doubt the technology, but because sustainment is not a playground. In our domain, a "hallucination" isn't just a funny chatbot error—it is a readiness risk.

And operational readiness does not tolerate ambiguity without accountability.

## The Data Paradox in IPS

We are in the middle of a massive shift from ILS to IPS. We are finally moving away from static PDFs to structured, S-Series compliant digital ecosystems.

This creates a dangerous illusion:

> “We finally have enough data. Let’s feed it into a neural network and let it run the supply chain.”

This is where the narrative breaks. In sustainment, having "more data" rarely means having "more truth." Often, it just means we have:

- More fields that look precise but encode hidden assumptions
- More records that are consistent in format but inconsistent in meaning
- More gaps that only reveal themselves when we try to model tail risk

Compliance produces data. Readiness requires decisions. We must not confuse the two.

## Why "Provenance" Matters More Than "Prediction"

In civilian logistics, a black-box optimizer is fine. If it fails, a package arrives late. The cost is bounded.

In defense, the cost of a wrong recommendation is not bounded in the same way. A false confidence in stock posture or an optimized maintenance plan that collapses under operational tempo can trigger unplanned AOG (Aircraft on Ground) events.

The core problem isn't that AI makes mistakes—humans make them too. The problem is that **AI creates confidence without provenance.** It gives you an answer without showing the "why."

In our line of work, that is operational debt. This brings us to the core of my philosophy: **The Stop Point.**

## The Stop Point Protocol

My approach isn't to reject AI, but to enforce **bounded automation**. AI should accelerate analysis, compress complexity, and surface risks, but it must stop before it triggers an irreversible action.

Here is a simple mental model:

- **Automation is allowed** to accelerate the "OODA Loop" (Observe, Orient).
- **Automation is NOT allowed** to finalize the "Decide and Act" without human validation.

Here is how this protocol works in practice.

### 1) AI is excellent at detecting demand structure

Humans are terrible at understanding intermittent demand. We see patterns where there are none.

AI is far better at classifying demand behavior—distinguishing between "lumpy," "erratic," and "smooth" demand. It can move us away from single-point forecasts towards probabilistic scenarios. This isn't magic; it is just better math for uncertainty.

### 2) AI is the ultimate data janitor

A huge part of IPS data is messy—free text, inconsistent naming, operational shorthand.

AI is genuinely useful here. It can normalize maintenance narratives, extract entities, and map inconsistent descriptions into analytics-ready categories. It turns the library into a decision tool, without pretending the library *is* the decision.

### 3) But AI cannot be the Authority

This is the station where I get off the train.

If a model recommends not stocking a critical spare, delaying maintenance, or accepting a specific availability risk, that recommendation must be traceable. I need to see the assumptions, the inputs, and the sensitivity analysis.

If I cannot audit the decision, I cannot accept the risk.

## From Black Box to Glass Box

We do not need black boxes in defense support; we need **glass boxes**.

A glass box recommendation doesn't just give an answer. It answers three critical questions:

1. **What is the decision?** Example: Increase buffer stock for Part X, or trigger an engineering review.

2. **What is the uncertainty?** Example: Demand is sparse, and lead time volatility is high.

3. **What changes the decision?** Example: "If operational tempo increases by 10%, this buffer is no longer sufficient."

This is the "missing middle"—the decision layer between raw data and operational action.

## Conclusion

So, am I on the AI train?

Yes.

But I am not riding it to "full autonomy." I am riding it to a specific destination: **Decision support under uncertainty.**

If your AI roadmap cannot explain what the model assumes, quantify the uncertainty, or define the action threshold, you do not have a decision support system. You have a demo.

And demos do not keep fleets ready.