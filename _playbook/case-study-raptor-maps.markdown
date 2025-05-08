---
layout: best-practice
title: "Case Study: Raptor Maps"
order: 580

section: Design Frugally
chapter-tag: design-frugally

previous-page: implement-caching-batching-and-offline-features
next-page: become-carbon-aware
---

# Case Study: Raptor Maps

## Challenge

[Raptor Maps](https://raptormaps.com/) builds software for the solar industry. Its flagship product, Raptor Solar Sentry, provides asset owners and operators with better data, elegant automation, and integration with remotely operated robotics to more efficiently identify and remediate issues that impact a solar project’s revenue. Raptor Solar provides a digital twin of the solar asset and enriches it with data and analytics, including data gathered from IoT devices, ground inspections and aerial imagery. The company’s mission is to help the solar industry scale.

The solar industry has grown very quickly in the past five years and the average solar sites have become much larger. As a result, Raptor Maps has onboarded thousands of new assets with the average size of those assets continuing to grow. In addition, these solar assets are getting denser as more data flows into them. This is in part due to the integration of autonomous robotics into solar industry workflows. These robots can collect data (e.g. imagery) on equipment at a much higher frequency than human field technicians. Together, these trends of higher volume, larger size and greater density of assets present interesting challenges for the Product and Engineering teams in achieving a performant and scalable experience for the user.

As a result, in late 2023, many of the features across Raptor Solar were under strain. The amount of networked data had spiked, increasing emissions across the product suite (see [Minimize data transfer](minimize-data-transfer)) and degrading performance.

On the mobile app, some solar assets were simply too big to download. This loss of performance was resulting in (unplanned) obsolescence as users looked to buy new phones to keep up with the app’s memory requirements. In addition, some users were not able to use the mobile app in remote areas with low data signal as they were unable to stream the large amounts of data required to use the app.

Raptor Maps had to ensure that its digital twin could continue to scale with the industry from a performance and UX perspective. This case study explores how Raptor Maps achieved that, benefiting the environment, customers, and the bottom line.

## Objectives

- Establish a data model and user experience for the digital twin that could handle exponential scale in the solar industry
- Support users in remote environments with limited connectivity
- Increase weekly active users of interactive maps across web and mobile
- Reduce the cost of networked data
- Ensure all API calls returned in under 5 seconds
- Reduce exports of data and maximize in-app value

## Approach

- **Progressive loading:** implemented pagination that matched the user's mental model. Instead of loading all raw data, Raptor Maps aggregated data to provide summaries, allowing users to load more information as they explored the map.
- **"Just-in-time" networking:** sent only the data packets that users need for majority use cases and allowed them to pull further data via straightforward UI. For example, applying default settings to encourage users to download less data and select more only as needed.
- **Aggressive caching:** cached data on web and mobile to ensure that users would not have to fetch the same information twice.
- **"Offline-First" mobile experience:** designed the mobile app assuming users would not have access to data signal and built it to gracefully handle long periods without connectivity.

## Impact

### 

**Environmental impact:** 

- Before these improvements, on a conservative estimate, loading the data on a 100 MW solar farm used 0.004 kWh of energy, equating to $0.17 in cloud computing costs, and 0.007 kWh of energy equating to $0.003 in device costs for our users on a daily basis.
- After this initiative, Raptor Solar loads only 0.75% of data by default, which saves 99.25% of energy costs each time a solar site is rendered in our web app - once per day on average.
- At scale, this equates to a daily savings of 0.3 kWh ($13.5) on the server side, and 0.6 kWh ($0.2) for end-user devices across the 100+ GW on the Raptor Solar platform. In future, once they have digitized the rapidly growing 1.4+ TB of installed PV solar globally, this equates to a daily savings of 39.5 kWh ($1,883) on the server side, and 80.3 kWh ($28.9) for end-user devices**. That is enough energy to power an electric vehicle (EV) for roughly 150 miles.
- These are conservative estimates as they anticipate that each solar site will likely be loaded more frequently than once daily.

**Performance Improvements:**

- Improved load speeds by 133x, making it possible to quickly load even the largest solar farms.
- Mobile app users can now use the product in areas without cell coverage.
- Eliminated unplanned obsolescence as users no longer need to upgrade phones to handle memory requirements.

**Business Impact:**

- Over 200% increase in year-over-year engagement for the web-based map experience.
- Dramatically reduced the number of API calls needed to use web and mobile products.
- Higher engagement with map products led to the discovery of more use cases.
- The offline-first mobile app enabled more scenarios where users have no coverage.

## Key Takeaways

- **Simplicity enhances value:** simplifying UX with larger building blocks proved that "less is more." The decrease in granularity prevented users from getting overwhelmed by data while allowing better performance.
- **Strategic data grouping:** grouping data provides more actionable and valuable information to customers while reducing networking costs, allowing users to pull more relevant granular data when needed.
- **Climate-positive changes require careful design:** The team had to be sensitive to any added friction and validate through discovery that sustainability improvements did not degrade usability.
- **Sustainability aligns with best practices:** Raptor Maps proved that climate-conscious product management and engineering are synonymous with best practices and drive great results for both business and customers.

## Future Steps

- Continue to apply these principles across our products as Raptor Maps scales.
- Reduce the data downloaded to a mobile device to more focused datasets based on user’s specific needs.
- Compress all images taken in the mobile app to reduce networked data further.
- Explore additional optimization techniques for the digital twin as the solar industry continues to grow

## Conclusion

Raptor Maps successfully transformed the Raptor Solar platform to handle the rapid growth and increasing data density of the solar industry with a fully scalable digital twin. By implementing thoughtful data loading strategies and designing for offline use, they not only reduced energy consumption and costs but also significantly improved the user experience. This case study demonstrates how sustainability considerations can drive innovations that benefit environmental, business and customer objectives, creating a win-win-win scenario for all stakeholders in the solar ecosystem.