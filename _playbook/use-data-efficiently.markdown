---
layout: best-practice
title: "Use Data Efficiently"
order: 120
icon: /assets/climate-icons/Icon-Chart.svg
number: "09"

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: measure-environmental-impact-of-ai
next-page: prioritize-sustainable-ai-design


matter: |
  Smart data management isn’t just good practice—it’s also better for the planet. As a PM, you can participate to storing and moving around less data. It reduces energy use and emissions, and keeping only what you need can actually improve model performance and avoid overfitting. Plus, using the right data for the right model and architecture, helps cut down on processing time, saving energy and water. As PMs, we have a real opportunity here: by championing quality over quantity, we can guide our teams to build better-performing AI while shrinking its environmental footprint.

do: |
  - Collect only strictly necessary data. Work with your stakeholders (e.g., legal, design, analytics teams) to clearly define essential data points for each product feature, removing non-essential or redundant data collection. Drive better data efficiency practices by simply asking: Do we really need this data?

  - To address concerns around potential loss of insights due to lack of data, emphasize data [quality over quantity](https://openai.com/index/scaling-laws-for-neural-language-models/?utm_source=www.theneurondaily.com&utm_medium=referral&utm_campaign=american-vs-chinese-ai), demonstrate through pilots how targeted, minimal data sets can deliver equal or better product performance with significantly reduced costs and risks.

  - Stay tuned with ever-evolving techniques. For example, in January 2025, [DeepSeek](https://arxiv.org/abs/2501.12948) showed that AI can reason well [without massive training datasets](https://openai.com/index/scaling-laws-for-neural-language-models/?utm_source=www.theneurondaily.com&utm_medium=referral&utm_campaign=american-vs-chinese-ai)— they achieved this through reinforcement learning, allowing their model to improve via trial and error. It’s about smart training, not more data.

  - Once you identify the data you need, you can help your technical team implement strict data retention policies such as storage period per type of data, and minimize dark data (the unused and unnecessary data), taking up a lot of storage.

  - If you are not sure the data will remain unused, then encourage for dark data to be stored locally for future potential use. You can extend this approach to your vendors SLAs (service level agreements) and SLOs (service-level objectives) (e.g. reduce retention time for log files).

  - With your data team, save unnecessary processing by investing a lot in data pre-processing to insure data hygiene and increase data quality. Avoid the “Garbage in - Garbage Out” effect and optimize response quality from the get go

  - Recommend the centralization of your data as well as the use of lightweight formats (e.g., JSON, Avif) to minimize data movements and migrations.

  - Implement data **compression** to reduce the number of bits to represent some data. (Could use ML for it keeping in mind the carbon footprint it may generate).

  - Support data pipelines optimization by reducing redundancy and enable answers caching with your engineering team.

  - Whenever possible, use open source data sets (rather than emitting new GHGs while building your own data pipeline) e.g. leveraging [Hugging Face](https://huggingface.co) & [Kaggle](https://www.kaggle.com/datasets).

  - If your application does not need live or “on demand” data collection, consider demand shifting (when/where there is green energy available).

success: |
  - 🧑💰 Optimized Data Processing and Management for Enhanced Application Performance

  - 🧑💰 Efficient utilization of data centers and servers for greener operations

consider: |
  Regularly audit and delete outdated or unused data. Don’t forget about staging or dev environments — these often hold redundant data that gets overlooked.
---

<div class="bigquote">
  <span class="highlight">"Clean, Lean Data Is the Cornerstone of AI Sustainability"</span>
</div>

