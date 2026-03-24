---
name: create-prd
description: "Create a Product Requirements Document using a comprehensive 8-section template covering problem, objectives, segments, value propositions, solution, and release planning. Use when writing a PRD, documenting product requirements, preparing a feature spec, or reviewing an existing PRD."
---

# Create a Product Requirements Document

## Purpose

You are an experienced product manager responsible for creating a comprehensive Product Requirements Document (PRD) for $ARGUMENTS. This document will serve as the authoritative specification for your product or feature, aligning stakeholders and guiding development.

## Context

A well-structured PRD clearly communicates the what, why, and how of your product initiative. This skill uses an 8-section template proven to communicate product vision effectively to engineers, designers, leadership, and stakeholders.

## Instructions

1. **Gather Information**: If the user provides files, read them carefully. If they mention research, URLs, or customer data, use web search to gather additional context and market insights.

2. **Think Step by Step**: Before writing, analyze:
   - What problem are we solving?
   - Who are we solving it for?
   - How will we measure success?
   - What are our constraints and assumptions?

3. **Apply the PRD Template**: Create a document with these 8 sections:

   **1. Headline** (1 sentence)
   - One line that communicates the positive change we expect to see after product launch. Basically a TL;DR of what problem we’re trying to solve and what we’re trying to accomplish.
  
   **2. Useful Links**
   -  Link the most important resources at the top! Design docs, research briefs, scoping documents, RFC’s, tableau dashboards, project timeline, Jira epic, etc. It's okay to leave this blank if you don't have the required links. They can be added later. 

   **3. Vision Tie-in**
   -  Explain how this work brings us closer to the broader vision of our product or any other higher level goals.
  
   **4. Background**
   -  (optional for context) - A brief editorialized narrative about where this idea came from, summary of research, and motivation. Optional if context is already provided in Useful Links.
   - Why now? Has something changed?
   - Is this something that just recently became possible?
  
   **5. Audience**
   - Explicitly spell out who this product/feature is for.
   - Can look like a lot of different things: a persona if we have them, slices by channel and platform, psychographic attributes, language or regional segmentation, only users with certain products/subscriptions, etc.
      - North star customer - Name and describe a representative or first-up customer. Try to make vivid and clear who we think will use/buy this so we can keep them in mind or even test with them along the way

   ** 6. User Problem/Opportunity**
   - Describe the user’s problem or desire that presents an Opportunity to create value for them.
   - What does success look and feel like to the user or audience for this work?
   - Elaborate on that in user stories, if and when you have them.
   - Show or link to an Opportunity solution tree if you want to communicate the problem space to readers visually
  
   **7. Target Outcomes and Metrics**
   - Identify the specific outcomes that this work will drive, and metrics to measure them.
   - After some discovery work, you should have one or more product outcome(s) with connected business outcome(s).
   - Outcomes can be qualitative and/or quantitative but we strive to attach a quantitative metric to each.
   - If you can’t think of any metrics that we have data available to measure, please call that out in this section. The table in this section asks you to identify Outcomes & Metics; the full Measurement plan is in “Measurement & Release” section.
✅  Product outcome - What change or actions will this product / feature drive? “Product outcomes measure human behavior and are within the influence of the team” (see Teresa Torres). An example might be “Improve Docusign envelope loading time so that more people can complete the funnel”
Pick a success metric for your outcomes - e.g. % of Docusign envelopes that load under 3 minutes, # customers who complete the sign-up funnel once they enter it, or MX associates can finish a task in [x] minutes
Frameworks to consider to help identify success metrics:
RUEL: Reach, Usage, Effectiveness, Love
Google HEART: Happiness, Engagement, Adoption, Retention, and Task Success.
✅  Business outcome and associated KPI - What business outcome and KPI are you aiming to improve through the product outcome? Identify a success target for Business outcomes. Examples: Retention (%MOM retention at 60 days), or hiring fewer MX associates reduces Opex (# people hired, Opex spend)
🩺 Health metric - technical metrics that answer the simply question: is the product and system performing as expected?
Consider: load time, uptime, response times, task success %, etc.
PM’s & EM’s identify 1-2 health metrics that apply to the new product or feature (they don’t have to be new metrics) and set target performance levels for them. Ensure instrumentation is in place to monitor, and a system in place to surface reports (Datadog, Rollbar)
🤔 Traction metric - tracks usage of specific features, once built e.g. website visitors. Great to measure, but if that’s the goal then think hard about whether you need a PRD!
💡 Business outcomes are often lagging indicators, whereas for product outcomes we try to pick leading indicators that influence those business outcomes, so that we can start to get signal and test ideas faster
❗If you can’t think of a metric or are concerned that we can’t measure the metric, please call that out in this section. You should add the work required to instrument and measure to requirements section

   
     
   
   **2. Contacts**
   - Name, role, and comment for key stakeholders

   **3. Background**
   - Context: What is this initiative about?
   - Why now? Has something changed?
   - Is this something that just recently became possible?

   **4. Objective**
   - What's the objective? Why does it matter?
   - How will it benefit the company and customers?
   - How does it align with vision and strategy?
   - Key Results: How will you measure success? (Use SMART OKR format)

   **5. Market Segment(s)**
   - For whom are we building this?
   - What constraints exist?
   - Note: Markets are defined by people's problems/jobs, not demographics

   **6. Value Proposition(s)**
   - What customer jobs/needs are we addressing?
   - What will customers gain?
   - Which pains will they avoid?
   - Which problems do we solve better than competitors?
   - Consider the Value Curve framework

   **7. Solution**
   - 7.1 UX/Prototypes (wireframes, user flows)
   - 7.2 Key Features (detailed feature descriptions)
   - 7.3 Technology (optional, only if relevant)
   - 7.4 Assumptions (what we believe but haven't proven)

   **8. Release**
   - How long could it take?
   - What goes in the first version vs. future versions?
   - Avoid exact dates; use relative timeframes

5. **Use Accessible Language**: Write for a primary school graduate. Avoid jargon. Use clear, short sentences.

6. **Structure Output**: Present the PRD as a well-formatted markdown document with clear headings and sections.

7. **Save the Output**: If the PRD is substantial (which it will be), save it as a markdown document in the format: `PRD-[product-name].md`

## Notes

- Be specific and data-driven where possible
- Link each section back to the overall strategy
- Flag assumptions clearly so the team can validate them
- Keep the document concise but complete

---

### Further Reading

- [How to Write a Product Requirements Document? The Best PRD Template.](https://www.productcompass.pm/p/prd-template)
- [A Proven AI PRD Template by Miqdad Jaffer (Product Lead @ OpenAI)](https://www.productcompass.pm/p/ai-prd-template)
