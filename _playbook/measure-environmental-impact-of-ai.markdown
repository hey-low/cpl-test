---
layout: best-practice
title: "Measure environmental Impact of your AI Implementations"
order: 110
icon: /assets/climate-icons/Icon-Brain.svg
number: "08"

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: build-sustainable-ai-products
next-page: use-data-efficiently


matter: |
  As AI-powered solutions become integral to modern products, their environmental impact must be carefully assessed to ensure long-term sustainability. AI models consume significant energy across training, inference, and operations, with their carbon footprint also encompassing hardware emissions, water use for cooling, and the environmental cost of retired equipment. To create responsible AI products, product leaders must benchmark and monitor their solutions across their full lifecycle, from model training and deployment to ongoing inference and product end-of-life. This means tracking performance and user adoption, as well as operational carbon footprint, embodied emissions, and energy efficiency at each stage.

do: |
  - First things first, make environmental tracking part of your product metrics. Influence your technical teams to adopt and regularly report on metrics such as carbon emissions and energy usage using open-source tools and libraries like the [Green Software Foundation’s Software Carbon Intensity Specification (SCI)](https://sci.greensoftware.foundation/) Cloud Carbon Footprint.

  - Work with your data or infrastructure teams to track compute usage and energy estimates across all AI product environments, such as Data storage, Cloud platform, AI development frameworks, MLOps pipelines, Version Management Systems, and Monitoring and Logging Systems.

  - If you have the resources, think of incorporating lifecycle assessments, starting with the processing of AI models, hardware manufacturing, and data center emissions. If faced with cost concerns, leverage freely available tools (like open-source carbon footprint calculators) or start with lightweight pilot measurements to demonstrate initial value.

  - Push for transparency in model and vendor selection:
    - Use “model cards” that document the features and performance characteristics of AI models in a consistent and standardized form. Check out [Hugging Face](https://huggingface.co/spaces/AIEnergyScore/Leaderboard) guides that disclose the environmental footprint of a wide range of models with their Energy Score for AI models proposal.
    - Demand detailed energy consumption reports directly from your vendors such as cloud providers or labs, since they are best-positioned to supply accurate figures.

  - Track the [inference](https://www.notion.so/Glossary-c2c6f6bbf55849a0887ea495e54e7cd7?pvs=21) footprint at the task level, as for the same task, different models can use different amounts of energy$^3$.

  - Get ahead of regulations: For example, [The European AI Act](https://artificialintelligenceact.eu/), the first comprehensive set of regulations on AI, has mandated the publishing of information about the environmental impact of creating foundational models, with significant penalties for non-compliance. As an AI system designer, you can proactively use model cards mentioned above to compare the environmental footprints of the models you use.

  - Generate usage-based estimates for inference: [GenAI Impact](https://genai-impact.org/) offers an open-source tool called [EcoLogits](https://ecologits.ai/latest/) that provides usage-based estimates for inference from the largest AI services and can be incorporated into AI projects.

  - Prefer open-source models when possible: They’re more transparent, offer greater visibility into energy usage and environmental impact, and are often lighter-weight.

success: |
  - 🌍 Energy efficiency measures leading to decreased consumption

  - 🧑💰 Measures to extend the longevity of hardware, reducing e-waste

  - 🌍 Inclusion of environmental metrics in product analytics and reporting

consider: |
  Include sustainability metrics in your product analytics. Start adding data like energy usage, water consumption, and Hardware Lifecycle Analysis impact to your dashboards — right alongside performance and adoption. Track measurable energy efficiency improvements overtime. Additionally, you can implement control tools such as minimum quality threshold before pushing new model versions after training to avoid huge transfer for less quality. Start  and go beyond carbon footprint emissions and include water impact and full hardware Life Cycle Analysis (LCA).
---

<div class="bigquote">
  <span class="highlight">"Tokens per watt per dollar"—the sweet spot where energy, compute power, and intelligence meet—will be a game-changing formula for driving GDP growth."</span>
</div>

<p style="text-align:center;">—Satya Nadella, <a href="https://www.linkedin.com/in/satyanadella?miniProfileUrn=urn%3Ali%3Afsd_profile%3AACoAAAEkwwAB9KEc2TrQgOLEQ-vzRyZeCDyc6DQ">Chairman and CEO at Microsoft</a></p>