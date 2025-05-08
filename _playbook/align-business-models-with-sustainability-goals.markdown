---
layout: best-practice
title: "Align business models with sustainability goals"
order: 570
icon: /assets/climate-icons/Icon-Hand$.svg
number: "25"

section: Discover Mindfully
chapter-tag: discover-mindfully

previous-page: reuse-and-recycle
next-page: design-frugally


matter: |
  Digital products are increasingly adopting consumption-based pricing models—charging customers based on the amount of usage, such as compute time, API calls, or data storage. On the surface, this may seem to encourage green user behavior by promoting frugality and conscious consumption. For instance, customers who pay per gigabyte of data processed might be more inclined to clean up unused files or avoid unnecessary queries. However, in practice, these models can create misaligned incentives that prioritize revenue over environmental impact or user well-being.

  For instance, a SaaS product feature might auto-trigger other features with resource-heavy processes (like syncing large datasets on each dashboard refresh), inflating usage and emissions. Likewise, if users are billed by data volume, they might avoid data compression or pruning—even if it reduces their footprint and costs.

  In some cases, product teams may be pressured to *optimize for engagement over efficiency* —incentivizing usage behaviors that generate revenue but degrade performance, increase server load, or encourage digital waste (e.g., storing duplicate files, processing unnecessary transactions, or rendering rarely-used UI elements) —ultimately increasing digital waste.  

do: |
  - Avoid tying pricing directly to system-level ‘work’** that the customer doesn’t control (e.g., CPU cycles, number of background tasks, or memory usage), as this disincentivizes performance improvements and energy-efficient development.

  - Consider pricing based on outcomes or tiered access that reflects value**, not raw usage. For instance, instead of charging per compute-hour, charge per successful analysis or decision-support outcome.

  - Meter on fundamental and meaningful units of value**—like the number of end-users served or transactions completed—rather than system internals. This keeps technical implementations flexible and open to optimization without risking revenue loss. [Delete old user accounts and old data](delete-old-accounts-and-old-data)
  
  - Give users control over feature selection.** Allow them to opt in to resource-intensive features only when needed. This not only improves user experience by avoiding feature bloat or performance drag, but also reduces unnecessary compute load. For example, allow a user to disable real-time syncing or to schedule it during off-peak hours. Check out [Promote green user behaviors](promote-green-user-behaviors)

  - Bake sustainability into pricing transparency. Let customers understand the environmental and financial implications of their usage. For instance, offering dashboards that show energy estimates alongside billing can help shift behavior toward greener practices.

  - [Chapter 5 - Design Frugally](design-frugally)

success: |
  - 🧑💰 Enhanced user experience leading to improved conversion rates and overall satisfaction

  - 💰 Optimization leading to reduced cloud expenditure

  - 🧑 Increased adoption of product features that promote sustainability

  - 🧑 Streamlined product performance, exemplified by faster load times

  - 🧑💰 Efficient utilization of data centers and servers for greener operations

  - 🧑💰 Optimized system design and resource allocation for better performance and lower costs

  - 🧑💰 Optimized Data Processing and Management for Enhanced Application Performance

  - 🌍 Energy efficiency measures leading to decreased consumption

consider: |
  By aligning pricing strategy with sustainability principles, you create a business model that rewards efficiency, supports user trust, and contributes to reducing digital carbon emissions—without sacrificing growth or innovation. 

  The effort to avoid tying your business to inefficiency will likely require cross-functional collaboration and leadership buy in. It may involve changes to the business model to incentivize efficiency and still be profitable. Organizations should empower product managers to raise concerns around efficiency from the start. It is better for the business, users, and the climate when a product is well-designed and efficient.
---

<div class="bigquote">
  <span class="highlight">"Tokens per watt per dollar"—the sweet spot where energy, compute power, and intelligence meet—will be a game-changing formula for driving GDP growth."</span>
</div>

<p style="text-align:center;">—Satya Nadella, <a href="https://www.linkedin.com/in/satyanadella?miniProfileUrn=urn%3Ali%3Afsd_profile%3AACoAAAEkwwAB9KEc2TrQgOLEQ-vzRyZeCDyc6DQ">Chairman and CEO at Microsoft</a></p>