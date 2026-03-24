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

3. **Apply the PRD Template**: Create a document using this template:
    ### Readme (how-to use this template) 

    **Purpose**: This PRD template is designed to support cross-functional P/D/E teams doing both product discovery and delivery. A good PRD is a living document that is the source of truth for the builder team, and a starting point for anyone who wants to learn more. Sharing PRDs early and often helps make sure we get a wide variety of perspectives, identify risks and dependencies early, and stay aligned on what we’re building.

    **Philosophy**:

    * The sections here cover product discovery, delivery, release and measurement. This is *not* \*\*\*\*to suggest that such stages should be accomplished strictly sequentially: We should be doing [continuous product discovery](https://www.producttalk.org/2021/08/product-discovery/) with our users, incorporating what we learn into delivery. These activities will often overlap, circle back and evolve along side of each other. Do not treat them as sequential stage-gates, or you will find yourself slipping down a very large Waterfall 🛶  
    * We do the work as a team. We should be “Solving problems *collaboratively* in a give and take between product, design and engineering, rather than *sequentially* (product manager writing up requirements, the designer providing a design that satisfies those requirements, and engineers building to those requirements).” \- [Marty Cagan](https://svpg.com/discovery-vs-documentation/)

    **When is this required?**

    * ✅  Required when developing a new feature or product that we will release in production and support to (at least some of) our internal or external users. An internal technical service qualifies as a user, so serving brand new functionality as an internal service should have a PRD to align on requirements with the consuming squad(s).  
    * ❌  A PRD is not always appropriate and can be overkill.  
      * We might just need to communicate some user insights (better artifact: User research report).  
      * We might be optimizing an existing feature and seeing impact on traction metrics (better artifact: [Notion card to scope](https://www.notion.so/d6b01af286d64d5eb3422b0f732744fd?pvs=21), results summary)  
      * Doing a tooling introduction or re-platforming is better communicated with a Request for Comment (artifact: [RFC](https://github.com/ArcadiaPower/rfcs)) and then planning tasks in Notion/Jira.  
    * ❌  A PRD is not synonymous with a workstream card in Notion. We create cards, for either projects or initiatives, that describe specific work to complete within a certain timeframe. A PRD can be attached to a Notion card, and the card might describe completing a scope (e.g. Phase 1), but not all cards in our Roadmap are PRDs.

    **Definitions & Detailed How-to’s c***an be found in each section under How-to toggles* 🔽

    ### Introduction

    ###### How-to

    **Headline** \- One line that communicates the positive change we expect to see after product launch. Basically a TL;DR of what problem we’re trying to solve and what we’re trying to accomplish. Example: “Empower major energy brands to offer or revoke automated utility bill remittance as part of an engaging branded experience to their customers.”

    **Useful Links** \- Link the most important resources at the top\! 🔗  Design docs, research briefs, scoping documents, RFC’s, tableau dashboards, project timeline, Jira epic, etc.

    **Vision Tie-in** – Explain how this work brings us closer to the broader vision of our product or any other higher level goals.

    **Background** (optional for context) \- A brief editorialized narrative about where this idea came from, summary of research, and motivation. Optional if context is already provided in Useful Links.

    ###### Headline

    ###### Useful Links

    * 🖇️  Design docs, research briefs, scoping documents or task lists, tableau dashboards, project timeline, release notes, etc.  
    * 🖇️  Jira epic (when appropriate)  
    * 

    ###### Vision Tie-in

    How does this work relate to our broader Arcadia goals? For example, how does a platform initiative get us closer to our vision of moving upstream from just providing raw data towards more value-added services like Commercial Energy Management?

    ###### Background

    ### Discovery

    ###### How-to

    **Audience** \- Explicitly spell out who this product/feature is for. Can look like a lot of different things: a persona if we have them, slices by channel and platform, psychographic attributes, language or regional segmentation, only users with certain products/subscriptions, etc.

    * ⭐ North star customer \- Name and describe a representative or first-up customer. Try to make vivid and clear who we think will use/buy this so we can keep them in mind or even test with them along the way

    **User Problem/Opportunity** \- Describe the user’s problem or desire that presents an Opportunity to create value for them. What does success look and feel like to the user or audience for this work?

    * Elaborate on that in user stories, if and when you have them.  
    * Show or link to an [Opportunity solution tree](https://www.producttalk.org/opportunity-solution-tree/) if you want to communicate the problem space to readers visually

    **Target Outcomes and Metrics** \- Identify the specific outcomes that this work will drive, and metrics to measure them. After some discovery work, you should have one or more product outcome(s) with connected business outcome(s). If your sole goal is to improve a traction metric, you may be doing optimization of an existing feature and you may not need a PRD for that. Outcomes can be qualitative and/or quantitative but we strive to attach a quantitative metric to each.

    🎯 PRD authors should work with a Data Analytics colleague on identifying metrics and creating a measurement plan. [Read more on this here](https://docs.google.com/document/d/1F_kD4riG-WGCwOIVxDysYnpYJV2sethQP8K2Jd3LVGc/edit?usp=sharing)\! If you can’t think of any metrics that we have data available to measure, please call that out❗in this section. The table in this section asks you to identify Outcomes & Metics; the full Measurement plan is in “Measurement & Release” section.

    * ✅  Product outcome \- What change or actions will this product / feature drive? “Product outcomes measure human behavior and are within the influence of the team” (see [Teresa Torres](https://www.producttalk.org/2020/05/product-outcomes/)). An example might be “Improve Docusign envelope loading time so that more people can complete the funnel”  
      * Pick a success metric for your outcomes \- e.g. % of Docusign envelopes that load under 3 minutes, \### customers who complete the sign-up funnel once they enter it, or MX associates can finish a task in \[x\] minutes  
      * Frameworks to consider to help identify success metrics:  
        * RUEL: Reach, Usage, Effectiveness, Love  
        * Google HEART: Happiness, Engagement, Adoption, Retention, and Task Success.  
    * ✅  Business outcome and associated KPI \- What business outcome and KPI are you aiming to improve through the product outcome? Identify a success target for Business outcomes. Examples: Retention (%MOM retention at 60 days), or hiring fewer MX associates reduces Opex (\### people hired, Opex spend)  
    * 🩺 Health metric \- technical metrics that answer the simply question: is the product and system performing as expected?  
      * Consider: load time, uptime, response times, task success %, etc.  
      * PM’s & EM’s identify 1-2 health metrics that apply to the new product or feature (they don’t have to be new metrics) and set target performance levels for them. Ensure instrumentation is in place to monitor, and a system in place to surface reports (Datadog, Rollbar)  
    * 🤔 Traction metric \- tracks usage of specific features, once built e.g. website visitors. Great to measure, but if that’s the goal then think hard about whether you need a PRD\!  
    * 💡 Business outcomes are often lagging indicators, whereas for product outcomes we try to pick leading indicators that influence those business outcomes, so that we can start to get signal and test ideas faster  
    * ❗If you can’t think of a metric or are concerned that we can’t measure the metric, please call that out in this section. You should add the work required to instrument and measure to requirements section

    **Positioning & Competition** \- Who else is doing something like this? How are we different? What’s the story for our customers? If this is for internal use, describe the Alternatives instead, or delete this header.

    **Testing Assumptions** \- What are some assumptions that we are testing all together as a team (engineers, PM, designers, analytics)? Do we have a learning goal for the discovery work? Any technical assumptions about what we can or cannot do to surface and examine? Which assumptions represent our greatest risks?

    🔗 Reminder \- links to your most important discovery artifacts (user research, prototypes, research briefs, technical spikes, solution brainstorms, or experiments) go up top.

    ###### Overview and Business Context

    * 

    ###### User Problem & Opportunity

    * 

    ###### Target Outcome & Metrics

    * 

    ###### Positioning and Competition
    * 

    ###### Testing Assumptions

    * 

    ### Delivery

    ###### User Personas Stories 

    | As a(n) | I want to | So that |
    | :---- | :---- | :---- |
    |  |  |  |
    |  |  |  |

    ###### High-level Feature Requirements (functional & non-functional)

    * 

    ###### Cross-functional requirements (Operations, Marketing, Analytics) 

    * 

    ###### Designs (if applicable) 

    * User stories stepping through the design (step by step, what do they do, what happens in the back end, edge cases)  
    * Other data / behaviors on the designs not captured in the stories

    ###### Data model / changes \- what business / functional entities / processes do we need to model 

    * 

    ###### Data flows (data user story)
    * 

    ###### Analytics / math / data processing
    * 

    ###### Edge Cases 

    * 

    ###### Out of Scope 

    * 

    ###### Risks

    * 

    ###### What’s Next 

    * 

    ###### Security Concerns & Project Risks 
    * 

    ###### Collaboration and Dependencies 

    * 
      
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
- [Arcadia PRD - Template](https://docs.google.com/document/d/1nR7YElltn7nPEEbV_O-ImJ1oPHTbU6T-isr_9vK5arM/edit?tab=t.0)
