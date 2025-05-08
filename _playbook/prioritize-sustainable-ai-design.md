---
layout: best-practice
title: "Prioritize Sustainable AI Design"
order: 130
icon: /assets/climate-icons/Icon-AIStar.svg
number: "10"

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: use-data-efficiently
next-page: optimize-model-training


matter: |
  AI features can be powerful, but they often require a lot of compute and storage, so high energy use and environmental cost. As PMs who drive responsible innovation, we need to be thoughtful about when and how we use AI. That starts with asking the tough question: do we even need AI here? We also have the critical role to communicate sustainability principles to stakeholders, fostering collaboration as we make intentional choices that serve both users and the planet. 

do: |
  - Start with critical questions: What will be the climate impact of this new AI product?  Is AI the right technology to create the intended output here? Very often the answer is no. [More frugal and effective methods](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5012869), such as rule based scripting, may be applied.

  - Choose the right model for the right task following the sufficiency principle. Don’t default to LLMs, the aggregated emissions from end-user interactions with LLMs have the highest environmental impact. Instead use smaller, task-specific models whenever possible — they’re often just as effective and far more efficient.

  - Be intentional about GenAI features like summarization, translations, podcast creation. They are energy intensive and heavy in emissions. Avoid making them default. Instead, let users opt in with a clear prompt (e.g., “This podcast uses 3x more energy than text. Proceed?”)

  - Turn sustainable design into a feature— not a compromise. Add a “light mode” option, show users the impact they avoided by choosing it e.g.: “You saved X kWh by using this mode.” and incorporate educational tips, explain what it will use, and how it will be processed, even suggest more optimal solutions.

  - Understand tradeoffs. Bigger models might save inference time but burn more energy in training. Work with your tech team to find the right balance for your use case.

success: |
  - 🧑💰Enhanced user experience leading to improved conversion rates and overall satisfaction

  - 🧑💰Reduction in maintenance costs, reflecting efficient design and execution

  - 🧑**💰Accelerated development cycles emphasizing efficient resource use**

consider: |
  Continuously assess user and business needs to refine your system design. Look for opportunities to simplify, defer, or opt for lighter alternatives to reduce compute without compromising user experience. 
---

<div class="bigquote">
  <span class="highlight">A single ChatGPT query requires 2.9 watt-hours of electricity, compared with 0.3 watt-hours for a pre-genAI Google search, according to the International Energy Agency.</span>
</div>

<p style="text-align:center;"><a href="https://www.epri.com/research/products/3002028905">Powering Intelligence: Analyzing Artificial Intelligence and Data Center Energy Consumption</a></p>