---
layout: best-practice
title: "Case Study: Soft Disabling"
order: 580

section: Discover Mindfully
chapter-tag: discover-mindfully

previous-page: align-business-models-with-sustainability-goals
next-page: design-frugally
---

# Case Study: Soft Disabling - Sustainable Front-End Design Through Feature Deactivation

## Challenge

As digital products grow increasingly complex, climate conscious developers are exploring ways across the full stack to optimize applications for reduced energy consumption and lower infrastructure costs while maintaining user experience. [Vincent Offroy](https://www.linkedin.com/in/vincentoffroy/?originalSubdomain=fr) has pioneered "[**soft disabling**](https://medium.com/@offroy.vincent.dev/soft-disabling-fr-4fe2121473ce)"—an eco-design approach that temporarily deactivates rarely used features after prolonged inactivity rather than permanently removing them. Users can reactivate these features when needed, striking a balance between usability, sustainability, and cost-efficiency. If soft-disabled features remain unused, product teams can consider permanent deprecation.

Digital interfaces often contain numerous features with limited usage. Each feature, especially those requiring API calls, live data fetching, or high computational resources, contributes to infrastructure strain. This approach addresses a three-way dilemma in feature management:

- **API overhead:** Redundant network requests increase server load and energy consumption
- **Infrastructure costs:** Always-active features inflate hosting and maintenance expenses
- **User experience concerns:** Removing features outright may alienate specific user groups

Soft disabling relies on strong data-driven decisions to balance these factors in a way that is highly compelling - even when you have minimal stakeholder buy-in for climate conscious initiatives.

## Objectives

- Reduce energy consumption and infrastructure costs by deactivating rarely used features
- Preserve user experience by maintaining the option to reactivate features when needed
- Provide data-driven insights to guide future feature development and deprecation
- Lower application's carbon footprint without sacrificing functionality
- Create a sustainable approach to feature lifecycle management

## Approach

Soft Disabling introduces an adaptive front-end mechanism:

- **Track usage:** implement analytics to monitor how frequently users interact with each feature, establishing baseline usage patterns and identifying candidates for soft disabling. Ensure all tracking complies with privacy regulations, is covered in your terms of service, and respects user consent choices.
- **Automated deactivation process:** create mechanisms to automatically hide and disable backend resources for features that remain unused beyond a defined threshold (typically 2-4 weeks)
- **User-Friendly reactivation:** design intuitive “calls-to-action” (CTAs) - like buttons - that allow users to easily restore disabled features when needed, with minimal friction in the user experience.
- **Eco-Awareness Messaging:** develop subtle messaging to inform users about the sustainability benefits of feature deactivation, fostering understanding, acceptance and appreciation.
- **Progressive testing:** implement soft disabling gradually across feature sets, testing different thresholds and reactivation methods to find the optimal balance between resource savings and user satisfaction.

## Impact

Soft disabling can deliver significant environmental and technical benefits:

- **Technical improvements:** reduce unnecessary API requests, lowering energy use. For example, by soft-disabling a feature used by only 5% of users and responsible for 10% of daily API calls, Vincent estimates that this approach would result in a 7% reduction in server energy consumption and a 3% reduction in cloud computing costs.
- **Customer experience/UX:** improve application performance and responsiveness by lightening page loads, resulting in faster user experiences.
- **Business impact:** lower infrastructure costs through more efficient resource usage, and more sustainable scaling as user base grows. Reduce technical debt from maintaining unused features, and generate better insights into feature popularity and usage patterns.
- **User-centric sustainability:** users have control, ensuring accessibility to features while fostering eco-conscious engagement.
- **Carbon efficiency:** reduce server-side energy consumption from decreased computational demands and thereby lower your product’s carbon footprint.

## Key Takeaways

- **Eco-design requires balance:** soft disabling offers a middle ground between keeping unused features and removing them entirely.
- **Data-driven decisions are essential:** usage tracking ensures optimizations are based on actual behavior patterns rather than assumptions.
- **User control preserves experience:** allowing reactivation maintains accessibility while encouraging resource efficiency.
- **Small optimizations scale significantly:** even minor reductions in per-user resource consumption can produce massive sustainability gains at scale.
- **Sustainability can enhance UX:** removing clutter and focusing on frequently used features often improves the overall user experience.
- **User Communication is Important:** transparent communication with users about why features are being temporarily deactivated and the associated benefits (e.g., improved performance, reduced environmental impact) can foster understanding, acceptance and appreciation/kudos.

## Future Steps

What’s next for soft disabling?

- Develop machine learning algorithms to predict optimal disabling thresholds based on user segments and behavior patterns.
- Expand soft disabling to include more resource-intensive backend processes.
- Create more granular metrics to measure environmental impact of feature usage.
- Integrate with CI/CD pipelines to incorporate sustainability metrics into development workflows.
- Establish industry standards for sustainable feature management practices.

## Conclusion

Soft Disabling demonstrates how thoughtful design can align sustainability goals with business objectives and user needs. This is a great way to empower product teams with a clear implementation strategy that is data-driven and highly defensible, even where you have minimal stakeholder buy-in for climate conscious initiatives. By implementing intelligent feature management, organizations can reduce digital waste while maintaining functionality and user satisfaction. As digital products continue to grow in complexity, approaches like soft disabling will become increasingly important for creating sustainable software that minimizes environmental impact without compromising on quality or usability.