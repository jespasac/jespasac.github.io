---
layout: post
title: "Why FinOps Fails When It Stays in Engineering"
category: "Cloud Economics"
date: 2025-01-20
read_time: 6
excerpt: "Cost optimisation without Finance at the table is just expense cutting. Real FinOps is a governance discipline — and most organisations haven't figured that out yet."
---

Most FinOps programmes I've seen start the same way: an engineer notices the AWS bill is growing faster than the business, gets frustrated, and starts optimising. They right-size instances, delete orphaned snapshots, move workloads to Spot. The bill drops 15%. Everyone claps.

Six months later, the bill is back where it started.

This is the FinOps trap — and it's not a technical problem.

## The real problem is ownership

When FinOps lives inside Engineering, it gets treated as a technical hygiene exercise. Teams optimise when they have time, which means they optimise when there's no deadline, which means they rarely optimise. Cost is a side effect of building, not a first-class concern.

The deeper issue: **Engineering doesn't feel the financial consequence of cloud spend.** They feel the consequence of downtime, of slow deployments, of technical debt. But a $200k monthly AWS bill? That's Finance's problem.

Until it isn't.

> "If the team spending the money doesn't own the accountability for that money, you don't have a FinOps programme. You have a cost dashboard nobody looks at."

## What Finance doesn't understand (and why it matters)

The other failure mode is equally common: Finance owns the budget, sees the cloud bill as an opaque line item, and responds with blanket cuts. "Reduce cloud spend by 20%" becomes a mandate handed to Engineering with no context, no prioritisation, no understanding of which spend is strategic and which is waste.

Engineers comply by cutting the easiest things — often the wrong things. A monitoring tool gets axed. A development environment disappears. Technical debt accumulates because the infrastructure supporting good engineering practices was deemed non-essential.

This is governance without understanding. It's equally broken.

## FinOps as translation

What actually works is building FinOps as a function that sits between Engineering and Finance — not inside either.

The FinOps practitioner's core skill isn't cloud architecture or financial modelling. It's translation. Taking an engineering team's infrastructure decisions and expressing them in terms of business value and financial accountability. Taking Finance's budget constraints and expressing them in terms of architectural trade-offs.

This requires three things most organisations skip:

- **Shared vocabulary.** What does "unit economics" mean for your product? Cost per user? Cost per transaction? Cost per deployment? Defining this is a joint exercise between Engineering, Finance, and Product.
- **Accountability without punishment.** Teams need to own their cloud costs without fearing that visibility means budget cuts. The goal is informed decision-making, not surveillance.
- **Executive sponsorship that spans both sides.** FinOps programmes die when they report only to the CTO. They need a seat at the CFO's table too.

## The governance model that works

In practice, this looks like a monthly ritual where Engineering leads present their cost performance — not in AWS cost categories, but in business terms. "Our recommendation engine cost €X per 1,000 recommendations this month, down from €Y because we improved the query cache." Finance understands that. The CTO understands that. The CEO understands that.

That conversation changes behaviour more than any automated rightsizing policy.

---

The organisations getting FinOps right aren't the ones with the most sophisticated tooling. They're the ones where cloud spend is a shared language between the people building the technology and the people financing it.

That's a governance problem. And governance problems are solved with people and process, not dashboards.
