---
layout: best-practice
title: "Optimize AI Model Training and Inference"
order: 140
icon: /assets/climate-icons/Icon-Connect.svg
number: "11"

section: Build Sustainable AI Products
chapter-tag: sustainable-ai

previous-page: prioritize-sustainable-ai-design
next-page: refine-architecture


matter: |
  Training and running AI models can be highly resource-intensive, driving up costs and carbon emissions. The ICT (Information and Communication Technology) sector already accounts for 2–5% of global emissions and could reach 14% by 2040, [with data centers contributing to almost half of this growth](https://ciandt.com/ca/en-ca/article/climate-crisis-and-technology-sector).
  
  As PMs we may not control the code or the infrastructure, but we do influence key decisions and smart choices—like using smaller models, training efficiently and asking the right questions. This chapter intends to provide you with technical methods that reduce environmental impact, even without clear energy-use data that big tech companies (also main owners of data centers) do not share easily. These techniques don’t just help the planet — they can also speed up your team and reduce infrastructure costs.

do: |
  - Select the most energy efficient AI Framework (for example, PyTorch seems to be more energy efficient during the inference phase and TensorFlow during the training phase)
  
  - Use **pre-trained models** when possible, to save on processing. Quality open source pre-trained models are available to use as is or with transfer learning. E.g.: Mistral, Llama, DeepSeek, Hugging Face.
  
  - Choose **specialized and smaller models** over frontier general-purpose LLMs (e.g., smaller transformer models like [DistilBERT](https://arxiv.org/pdf/2402.13640) for NLP tasks). To overcome skepticism about effectiveness, pilot a smaller model to validate performance parity, sharing results transparently with stakeholders.
  
  - Use model **[pruning](https://dl.acm.org/doi/abs/10.1145/3295500.33561561)** which reduces the complexity of an already trained model by removing unnecessary components. It makes the model smaller and more efficient limiting computation time for your production environment.
  
  - **[Fine-tune](https://www.notion.so/Glossary-c2c6f6bbf55849a0887ea495e54e7cd7?pvs=21)** your model carefully, by freezing parameters of pre-trained models and introduce your own subset of parameters.
  
  - Leverage **random sampling** techniques when dealing with a very large dataset allows you to create a representative subset of data for training or evaluation of your model which can significantly reduce computation time
  
  - Practice [**distillation**](https://www.notion.so/Glossary-c2c6f6bbf55849a0887ea495e54e7cd7?pvs=21) to transfer knowledge from large, complex models (teachers) to smaller, efficient ones (students), reducing computational resources and energy consumption while maintaining performance.
  
  - Use Lower-Precision Data Types, leveraging [**quantization**](https://www.notion.so/Glossary-c2c6f6bbf55849a0887ea495e54e7cd7?pvs=21) (a memory optimization technique of running inference) to shrink model sizes. e.g.: float32, int8
  
  - Train and run models more efficiently. Schedule training when energy is cheaper or greener — like nights or in green-energy regions. Defer or queue time-intensive processes, like large model inferencing, for **batch processing.**
  
  - Encourage **Local or On-device Inference** for recurrent or predictable tasks to reduce cloud dependency.
  
  - Opt for **Edge computing** when possible. Smaller models are more adapted for processing and storage closer to the data source, reducing energy consumption.
  
  - Leverage [**Federated learning**](https://www.notion.so/Glossary-c2c6f6bbf55849a0887ea495e54e7cd7?pvs=21) to train a ML model across multiple devices or servers holding local data without sharing the actual data to limit model training and reduce processing time.
  
  - Practice Energy-aware AI Code Refactoring: Identify and refactor AI Code Smells that contribute to high energy consumption without sacrificing the accuracy or performance of these models.
  
  - Work with engineers to optimize hardware usage across development stages, set GPU power caps, and leverage batch processing.

success: |
  - 🧑💰Optimized system design and resource allocation for better performance and lower costs

  - 🌍 Energy efficiency measures leading to decreased consumption

  - 🌍💰Reduced water usage in operations

consider: |
  Ask engineers to report back with efficiency gains or performance trade-offs and have regular model reviews where environmental impact is discussed alongside accuracy and latency.
---

<div class="bigquote">
  <span class="highlight">"Learning algorithms are the seeds, data is the soil, and the learned programs are the grown plants. The machine-learning expert is like a farmer, sowing the seeds, irrigating and fertilizing the soil, and keeping an eye on the health of the crop but otherwise staying out of the way."</span>
</div>

<p style="text-align:center;">Pedro Domingos, <a href="https://www.goodreads.com/book/show/24612233-the-master-algorithm">The Master Algorithm: How the Quest for the Ultimate Learning Machine Will Remake Our World</a></p>