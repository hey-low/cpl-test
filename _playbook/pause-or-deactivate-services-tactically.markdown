---
layout: best-practice
title: "Pause or deactivate services tactically"
order: 650
icon: /assets/climate-icons/Icon-Pause.svg
number: "38"

section: Become Carbon Aware
chapter-tag: become-carbon-aware

previous-page: optimize-for-clean-energy
next-page: conclusion


matter: |
  We need to shift from Always-ON to Always-Available practice. 
  Temporarily disabling certain features or libraries based on energy consumption or server load is a strategic approach to software management. We can prioritize operational efficiency and environmental responsibility by reducing demand during peak load times or when energy is sourced from fossil fuels. 
  This method ensures that the software adapts to real-time infrastructural constraints, minimizing ecological impact. This approach can be applied to advertising services, analytics or any third-party integration not vital to the user experience.

do: |
  - Determine which features are essential and which can be temporarily disabled without severely impacting user experience (e.g., during the night or holidays)

  - Turn off development & test environments overnights and weekends

  - Implement real-time tracking of server load and energy sources

  - Design algorithms that can auto-disable features based on set thresholds

  - Inform users when certain features are temporarily disabled and the rationale behind it (see [Promote green user behaviors](promote-green-user-behaviors))

  - Create a mechanism for users to provide feedback on the impact of these decisions on their experience

  - Switch from Always-on to Always-Available

success: |
  - 🧑💰 Enhanced user experience leading to improved conversion rates and overall satisfaction

  - 💰 Optimization leading to reduced cloud expenditure

consider: |
  Determining which feature should be paused, scheduled or disabled entirely requires a strong understanding of your users’ journey. If you don’t feel that it is right for you, you should consider @Set up ultra eco-mode as an alternative. 
---

<div class="bigquote">
  <span class="highlight">"We need to shift from Always-ON to Always-Available practice."</span>
</div>

<p style="text-align:center;">Shanna Grafeld, Gartner</p>