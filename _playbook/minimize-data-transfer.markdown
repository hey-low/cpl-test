---
layout: best-practice
title: "Minimize data transfer"
order: 550
icon: /assets/climate-icons/Icon-Transfert.svg
number: "30"

section: Design Frugally
chapter-tag: design-frugally

previous-page: optimize-multimedia-files
next-page: kill-unused-features


matter: |
  While it is always better to avoid building features you’re not confident will be used (see [Remove non-essential features from the scope](remove-non-essential-features-from-the-scope)), you still have a chance to remove them afterward. Trimming product bloat and eliminating unused features or features with low business value is crucial for efficiency, cost-effectiveness, and environmental sustainability. It enhances the user experience, reduces waste, and aligns with user needs.

do: |
  - Measure the adoption rate and frequency of feature usage
  
  - Place the results in a matrix with four quadrants: low/high adoption and low/high frequency

  - Be diligent and pragmatic when assessing whether to keep or delete features with low adoption and usage frequency

  - Decommission selected features

  - Maintain clear documentation and dashboards of feature usage metrics

  - Define feature life expectancy and conditions/triggers for retirement in the Product Requirement Documents (PRD)
  
  - Implement a regular and structured process for retiring features/products, see [chapter 1](embed-sustainability-into-your-rituals)

success: |
  - 🧑💰 Accelerated development cycles emphasizing efficient resource use
  
  - 🧑 Minimization of technical debt for longer product life and efficiency
  
  - 🧑💰 Enhanced user experience leading to improved conversion rates and overall satisfaction
  
  - 🧑💰 Reduction in maintenance costs, reflecting efficient design and execution
  
  - 💰 Optimization leading to reduced cloud expenditure
  
  - 💰 Rigorous data security measures ensuring compliance and protecting user trust

consider: |
  We can apply the same logic for features to applications, services, and products. Users can vary depending on whether the feature is designed for internal purposes (developers, customer support, etc.) or end-users.
  Foster a culture of minimalism and assess with your designers and developers what would be required to decommission selected features. Will this affect other parts of the experience, code, or business? Be thorough in anticipating these changes.
  Although rarely used, some features may have a high perceived value by users and may be required to match the competition. In some cases, it will be justified to keep them, but it should not be the default.
---

<div class="bigquote">
  <span class="highlight">"Surprisingly, 20% of API endpoints remain unused for over 30 days."</span>
</div>

<p style="text-align:center;"><a href="https://blog.treblle.com/the-anatomy-of-an-api-in-2023-a-comprehensive-overview/">The Anatomy of an API in 2023: A Comprehensive Overview</a></p>