---
layout: best-practice
title: "Case Study: Leboncoin: Optimizing API Traffic for Sustainability and Performance"
order: 560

section: Design Frugally
chapter-tag: design-frugally

previous-page: minimize-data-transfer
next-page: kill-unused-features
---

# Case Study: Leboncoin: Optimizing API Traffic for Sustainability and Performance

## Challenge

[Leboncoin](https://www.leboncoin.fr/), France's leading online marketplace, faced a significant challenge with excessive API traffic consuming resources and inflating costs. The Promote team, responsible for delivering dynamic user messaging via pop-ins, banners, and notifications, was generating 522 million weekly API calls— 85% of those resulting in 404 errors.

This inefficiency required up to 120 server replicas and pushed database CPU usage to 60%, significantly increasing their carbon footprint and operational costs. As their digital footprint grew, they recognized the urgent need for a scalable, eco-conscious solution that would maintain platform functionality while reducing waste.

## Objectives

Leboncoin aimed to eliminate redundant API requests to:

- Reduce overall API traffic
- Decrease infrastructure requirements
- Lower energy consumption and carbon emissions
- Cut infrastructure costs
- Improve system performance

## Approach

As part of the [Apidays Sustainable Digital Challenge](https://www.apidays.global/sustainable-digital-challenge/), Leboncoin implemented a three-pronged solution within a single two-week sprint in December 2023:

- **Smart endpoint architecture:** created a new API endpoint to verify content availability before initiating further requests, preventing unnecessary processing when no relevant content existed.
- **Strategic caching:** Implemented caching mechanisms to prevent repeated unnecessary requests on page loads, reducing redundant calls that consumed resources.
- **Dynamic feature management:** Deployed feature flags to disable unused message placements, automatically reducing system strain for features with low utilization.

## Impact

The optimization strategy delivered immediate and substantial benefits:

- **Customer experience/UX:** enhanced user experience with faster load times and reduced bandwidth consumption.
- **Technical improvements**: significant technical and performance improvements, including:
    - Eliminated 3.62 billion API calls in the first week.
    - Reduced 404 error responses by 71.93%.
    - Decreased server replicas from 120 to 40.
    - Lowered database CPU usage from 60% to 20%.
    - Reduced database connections by 25%.
- **Business impact:** cut Kubernetes costs to one-third of previous expenses, and dramatically improved platform scalability.
- **Sustainability gains:** Saved 49.66 CPU cores (equivalent to powering down an AWS c6g.12xlarge instance) and reduced carbon emissions by an estimated 24 kg of CO₂ (based on [Teads Engineering](https://engineering.teads.com/sustainability/carbon-footprint-estimator-for-aws-instances/) carbon footprint estimator)

## Key Takeaways

- **Digital efficiency equals sustainability**: reducing digital waste is as critical as optimizing physical resources.
- **Small changes, big impact**: focused technical optimizations can yield billions of saved requests and substantial benefits.
- **Technical debt has environmental costs**: outdated architectures waste energy and resources.
- **Green engineering benefits everyone**: sustainability improvements enhance user experience, reduce costs, and boost performance.

## Future Steps

Leboncoin plans to further optimize their API architecture by extending these principles to other systems across their platform. They aim to continue monitoring and measuring the environmental impact of their digital operations, setting new benchmarks for sustainable development in the tech industry.

## Conclusion

Leboncoin's proactive approach demonstrates how rethinking fundamental aspects of API design can yield technical, financial, and environmental benefits. By integrating eco-design principles into their product strategy, they proved that eliminating digital waste benefits both business operations and environmental sustainability.