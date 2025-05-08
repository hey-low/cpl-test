---
layout: best-practice
title: "Set up ultra eco-mode"
order: 630
icon: /assets/climate-icons/Icon-Factory.svg
number: "36"

section: Become Carbon Aware
chapter-tag: become-carbon-aware

previous-page: promote-green-user-behaviors
next-page: optimize-for-clean-energy


matter: |
  When the grid has a high carbon intensity, also known as a “dirty grid”, your product emits more carbon emissions and greenhouse gases compared to when it's powered by clean energy, which has a low carbon intensity. High carbon intensity is often associated with fossil fuel-powered grids, where the production of a kilowatt hour (kWh) of electricity results in significant emissions. It's important to note that using energy during peak hours is directly linked to higher electricity costs, higher-emitting energy sources, and higher air pollution. To mitigate this impact, there are ways to adapt your product experience and activate an ultra eco-mode. By making your experience responsive to these fluctuations, you can greatly impact your business, your users, and the environment.

do: |
  - Identify users’ location and use existing tools to know users’ carbon intensity ([Carbon Aware SDK](https://github.com/Green-Software-Foundation/carbon-aware-sdk), [Watttime](https://www.watttime.org/) or [Electricity Maps](https://www.electricitymaps.com/))

  - Avoid loading media content when the grid is dirty and show alt text instead (let users click to open media), check out [Branch Magazine](https://branch.climateaction.tech/), it is a great example

  - Use darker colors and themes (less energy-intensive, especially on OLED screens), as a rule of thumb, follow the [Web Content Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/) (WCAG)

  - Encourage users to delay high-energy activities for low-carbon-intensity times and offer incentives, discounts, or rewards

  - Enable users to revert to the default experience if they want or need to

  - [Pause or deactivate services tactically](pause-or-deactivate-services-tactically)

  - [Implement caching, batching, and offline features](implement-caching-batching-and-offline-features)

  - [Promote green user behaviors](promote-green-user-behaviors)

success: |
  - 🧑 Increased adoption of product features that promote sustainability

  - 💰 Optimization leading to reduced cloud expenditure

  - 🌍💰 Adoption of cleaner electricity sources for operations

consider: |
  Before deciding what to keep, downgrade, or pause for your ultra eco-mode, it is important to  balance the impact of your measures on both their sustainable goal and the user experience. This requires a delicate balancing act, which can be achieved by gathering feedback before and after implementation.
  As users may resist change, it is important to anticipate and mitigate these concerns by explaining why these measures are necessary, letting them know when they happen, and sharing how these changes and adaptations make a difference. This will mitigate the negative impact on your brand.
  A helpful approach is to implement changes gradually over time rather than making abrupt modifications.
  Additionally, it is important to have a plan for when carbon intensity data is unavailable, including a fallback mode.
---

<div class="bigquote">
  <span class="highlight">[Branch](https://branch.climateaction.tech/) is an online magazine published by the [Green Web Foundation](https://www.thegreenwebfoundation.org/). Their site changes its design based on the quantity of fossil fuels on the grid to stay inside a carbon budget at all times. This example illustrates how to both adapt your experience and educate your users when the grid intensity is high.</span>
</div>
