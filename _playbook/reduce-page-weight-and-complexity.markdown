---
layout: best-practice
title: "Reduce page weight and complexity"
order: 520
icon: /assets/climate-icons/Icon-Forward.svg
number: "27"

section: Design Frugally
chapter-tag: design-frugally

previous-page: build-straight-paths-to-user-value
next-page: use-multimedia-wisely


matter: |
  Page weight has been increasing tremendously over the past decade, with significant implications for both users and the environment. Between 2014 and 2024, the median desktop page size grew by 120% (an increase of 1.4 MB), while the median mobile page size surged by 357% (an additional 1.8 MB). Images are the largest contributors to page weight.

  These bloated page sizes have serious consequences. Heavier pages increase CPU usage and obsolescence, contributing to higher energy consumption and carbon emissions. They also exacerbate digital inequality, disproportionately affecting users with older devices or slower internet connections.

do: |
  - [Use multimedia wisely](use-multimedia-wisely)

  - [Optimize multimedia files](optimize-multimedia-files)

  - Remove unnecessary or unused code (scripts, frameworks, and plugins) and limit their use

  - Remove duplicate modules in JavaSscript bundles

  - Reduce the impact from third parties (check [BuiltWith](https://builtwith.com/) and [Are my third parties green](https://aremythirdpartiesgreen.com/))

  - Avoid infinite scroll and carousels. Prefer pagination and “load more” options.

  - Use lazy loading to reduce the elements downloaded

  - Use partial content reloading of specific elements (rather than the whole page)

  - Use [system](https://systemfontstack.com/), standard or web-safe fonts to avoid downloads

  - Use darker colors and themes (less energy-intensive on OLED)

  - Communicate in ways that do not rely on color alone, both for sustainability and accessibility

  - Minimize the number of steps needed for users to complete tasks

  - Consider designing to support older devices and slower speeds as a preference, when designing for inclusivity. Make KPIs that address performance under "worst case" conditions

  - Use asynchronous processing to optimize energy and performance

  - Prefer assisted input over auto-complete to reduce unnecessary server calls

  - Use up-to-date programming languages and frameworks for better efficiency
  
  - Prefer static page formats

success: |
  - 🧑 Streamlined product performance, exemplified by faster load times

  - 🧑💰 Reduction in maintenance costs, reflecting efficient design and execution

  - 💰 Optimization leading to reduced cloud expenditure

consider: |
  We encourage you to audit and optimize website or app assets regularly. These environmental, performance considerations and improvements will become an integral part of how cross-functional teams work once you @Include the planet in your brief & @Choose the right metrics . Education will be key for your organization and product squads to keep discovering best practices to apply. For this, nothing is better than to @Organize talks, raise awareness, and promote training and @Set up a climate working group. And don’t forget system inclusivity: design for older devices, slower connections, and question whether features even need an internet connection.
---

<div class="bigquote">
  <span class="highlight">"“Cultivate a culture of intentionality, precision and minimalism”"</span>
</div>

<p style="text-align:center;">Climate Product Leaders</p>