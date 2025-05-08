---
layout: best-practice
title: "Case Study: Creating Sustainable AI at Salesforce"
order: 160

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: refine-architecture
next-page: use-your-influence
---

# Case Study: Creating Sustainable AI at Salesforce

## Challenge

[Salesforce](https://www.salesforce.com/) is guided by its core values of trust, customer success, innovation, equality, and sustainability. These values are reflected in its commitment to responsibly develop and deploy new technologies like generative AI on behalf of stakeholders — from shareholders to customers to the planet.

The Large Language Models (LLMs) that power generative AI require enormous compute resources to function, resulting in negative environmental impacts like carbon emissions, water depletion, and resource extraction within the supply chain. As the world sets emissions and temperature records, which intensify extreme weather events and other climate impacts across the globe, the need to reduce planet-warming emissions has never been more dire. At a time when every additional ton of carbon emitted matters, the development of AI technologies should not exceed planetary boundaries.

While the hypothetical long-term sustainability benefits of AI are significant, with the potential to reduce global emissions by 5 to 10% by 2030, Salesforce also remains focused on minimizing environmental impacts in the short term.

## Objectives

- Minimize the environmental impact of AI development and deployment
- Balance the compute requirements of LLMs with sustainability goals
- Counter the trend of exponential growth in energy consumption by AI models
- Align AI development with global sustainability targets
- Demonstrate that powerful AI can be created with smaller environmental footprints

## Approach

- **Optimize models by focusing on domain-specific models:** Salesforce AI Research remains focused on developing domain-specific models, customized to their intended applications. For example, the CodeGen model, initially released in 2022, was one of the first LLMs to allow users to translate natural language into programming languages. The latest version, [CodeGen 2.5](https://www.salesforce.com/blog/codegen25/), has been optimized for efficiency through multi-epoch training and flash attention, resulting in a model that performs as well as larger models at less than half the size.
- **Use efficient hardware:** AI hardware manufacturers frequently unveil new versions with substantial efficiency enhancements. Salesforce AI Research has leveraged advancements in Google’s Tensor Processor Unit (TPU), training more recent models on TPU v4, which is 2.7x more efficient than TPU v3. Initial tests have found that the brand new TPU v5p outperforms the previous generation TPU v4 by as much as 2x.
- **Choose low-carbon data centers:** Salesforce trained its models in data centers powered by electricity that emits 68.8% less carbon than global average electricity. This resulted in 105 fewer tons of carbon dioxide equivalents (tCO2e) than if data centers with global average carbon intensity were used for training.
- **Implement sustainable prompt engineering techniques:** Salesforce built techniques into [Prompt Builder](https://www.salesforce.com/ca/artificial-intelligence/prompt-builder/) that optimize prompts for customer satisfaction, cost, and environmental sustainability, delivering top results with minimal resource usage.
- **Usage tracking and rate limits:** Salesforce implemented monitoring tools and usage thresholds within their [Einstein 1 Platform](https://www.salesforce.com/news/press-releases/2023/09/12/salesforce-platform-news-dreamforce/) built on Hyperforce. These features track AI system usage patterns and set appropriate limits to prevent excessive resource consumption, promoting mindful, responsible, and secure use of AI systems while reducing unnecessary energy expenditure.

## Impact

- **Energy conservation:** significant reduction in energy consumption through the use of efficient hardware and optimized models.
- **Carbon emissions reduction:** pre-training Salesforce’s AI models resulted in 48 tCO2e, 11 times less than the emissions of GPT-3.
- **Increased efficiency:** smaller models like CodeGen 2.5 are more cost-effective, easier to fine-tune, and operate faster, improving user experience.
- **Enhanced security:** local deployment of models decreases energy use, increases speed, and enhances security and personalization.

## Key Takeaways

- Embrace optimization: developing domain-specific models and optimizing for efficiency can drastically reduce the environmental impact of AI.
- Leverage efficient hardware: using the latest advancements in AI hardware can significantly enhance energy efficiency.
- Prioritize low-carbon operations: choosing low-carbon data centers and implementing sustainable AI techniques are crucial for minimizing environmental impact.

## Future Steps

Salesforce continues to advance sustainable AI practices through:
- Ongoing research into further model optimization techniques
- Exploration of next-generation energy-efficient hardware
- Development of more sophisticated carbon tracking and reduction tools
- Expansion of sustainable AI principles across their product ecosystem
- Collaboration with industry partners to establish sustainable AI standards

## Conclusion

Salesforce’s approach to creating sustainable AI demonstrates the significant impact that optimization, efficient hardware selection, and prioritizing low-carbon operations can have on reducing carbon emissions and improving operational efficiency. This case study serves as a model for other companies aiming to achieve sustainability goals through innovative technology solutions.

Learn more about Salesforce’s responsible AI development in their blog and join their Talent Community to get involved. Check out their Technology and Product teams for more information on their initiatives.