---
layout: best-practice
title: "Case Study: Illumina - Sustainable Cloud Storage for Genomic Data"
order: 660

section: Become Carbon Aware
chapter-tag: become-carbon-aware

previous-page: pause-or-deactivate-services-tactically
next-page: conclusion
---

# Case Study: Illumina - Sustainable Cloud Storage for Genomic Data

## Challenge

Illumina, a leading developer of life science tools and systems for large-scale genetic analysis, faced exponential growth in genomic data storage requirements in 2022. As the company expanded its product line and customer base, the amount of data stored in the cloud surged from 1 PB to 100 PB in eight years, with an additional 24 PB added in a single year (2021–2022). With this rapid growth in data, Illumina sought ways to optimize storage, maximize cost savings, and reduce carbon emissions.

## Objectives

- Optimize data storage on AWS, achieving cost savings, improving efficiency, and significantly reducing carbon emissions.
- Reduce carbon emissions by ~90% compared to on-premises solutions.
- Optimize data storage costs by 60% per TB.
- Enhance data management efficiency and customer experience.

## Approach

- **Choose a sustainable hosting provider:** Illumina used Amazon Web Services (AWS), which is on track to power its operations with 100% renewable energy by 2025. This aligns with the recommendation to use green hosting providers, significantly reducing the carbon footprint of their digital operations.
- **Optimize for clean energy:** using the AWS Customer Carbon Footprint Tool, Illumina tracked and optimized their carbon emissions. This tool provided insights into historical emissions, forecasted trends, and the estimated carbon emissions avoided by using AWS compared to on-premises data centers.
- **Promote green user behaviors:** by employing AWS's [Amazon S3 Intelligent-Tiering](https://aws.amazon.com/s3/storage-classes/intelligent-tiering/), Illumina automated storage cost savings by moving data based on access patterns. This minimized unnecessary energy consumption and encouraged more sustainable data management practices.
- **Set up ultra eco-mode:** Illumina was able to automatically transition infrequently accessed data to lower-cost storage tiers, ensuring energy-efficient data storage operations.
- **Educate and engage users:** Illumina ensured their teams were informed about the benefits of sustainable data management practices. This included optimizing job submissions and understanding the environmental impact of their data storage choices.

## Impact

- **Emissions reduction:** Illumina achieved an 89% reduction in carbon emissions by using AWS instead of on-premises data centers. During a 12-month period ending in November 2022, this amounted to a reduction from an estimated 2,657 metric tons of carbon dioxide equivalent (MTCO2e) to just 290 MTCO2e.
- **Cost savings:** by transitioning to Amazon S3 Intelligent-Tiering, Illumina saved 60% on storage costs per TB of data. This significant cost reduction allowed the company to allocate savings towards enhancing their service and software offerings.
- **Performance improvement:** the implementation of S3 Intelligent-Tiering streamlined internal workflows and simplified data management. Illumina's customers benefited from near-instant access to genomic data at a lower cost, accelerating their research and development efforts.

## Key Takeaways

- **Cloud storage optimization:** Moving to intelligent cloud storage solutions can dramatically reduce both costs and carbon footprint.
- **Automatic tiering benefits:** implementing solutions that automatically move data based on access patterns creates both efficiency and sustainability gains.
- **Carbon reduction at scale:** large-scale genomic data operations can achieve significant environmental benefits through thoughtful cloud architecture. Even smaller initiatives at behemoth organizations can have a big impact. 
- **Alignment of business and sustainability goals:** Cost optimization and carbon reduction can be complementary objectives when properly implemented.

## Future Steps

- Illumina plans to continue optimizing its data storage by moving additional data from research and development and from Illumina Connected Analytics into S3 Intelligent-Tiering.
- They are also exploring the use of Amazon S3 Storage Lens for enhanced visibility and actionable recommendations to further improve cost efficiency and energy usage.
- This ongoing digital transformation supports Illumina's mission to improve human health while maintaining a commitment to sustainability.

## Conclusion

Illumina's strategic approach to genomic data storage demonstrates how life sciences companies can address the exponential growth of research data while simultaneously reducing costs and environmental impact. By leveraging cloud technologies with automated data management capabilities, Illumina has created a scalable solution that supports both their business objectives and sustainability commitments. This case study shows that even with massive data requirements, companies can implement practical strategies that benefit their operations, customers, and the planet.