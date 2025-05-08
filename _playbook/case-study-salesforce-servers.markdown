---
layout: best-practice
title: "Case Study: Automated Server Decommissioning: Achieving Carbon Reduction at Scale for a Greener Future"
order: 640

section: Become Carbon Aware
chapter-tag: become-carbon-aware

previous-page: set-up-ultra-eco-mode
next-page: optimize-for-clean-energy
---

# Case Study: Automated Server Decommissioning: Achieving Carbon Reduction at Scale for a Greener Future

## Challenge

The tech sector plays a major role in global energy usage and carbon emissions — projected to account for up to [20% of global energy demands by 2030](https://www.mdpi.com/2078-1547/6/1/117). Data centers are major contributors, using over 205 terawatt hours of electricity each year ([IEA, 2022](https://www.iea.org/reports/data-centres-and-data-transmission-networks)), exceeding the energy consumption of entire countries like [Taiwan, Ireland, and Denmark](https://yearbook.enerdata.net/electricity/electricity-domestic-consumption-data.html).

Addressing this urgent issue, Salesforce remains committed to reducing energy usage and carbon emissions in data centers by optimizing and reducing servers, aligning with the company's sustainability values and pledge to [cut emissions in half by 2030](https://www.salesforce.com/company/sustainability/)). The [Salesforce Decommissioning Program](https://engineering.salesforce.com/automated-server-decommissioning-achieving-carbon-reduction-at-scale-for-a-greener-future/) (SDP) team leads this effort, aiming to retire more than double the number of servers compared to the previous year.

The team faced several key challenges:

- A complex, 16-step manual decommissioning process increased the probability for human error
- Lack of visibility into the project's progress
- Required manual intervention and meticulous investigation of each decommissioning failure case
- Inefficient and human-centric workflows hindered scalability, resulting in prolonged energy consumption and negative carbon impact

## Objectives

- Streamline and automate the server decommissioning process
- Reduce manual steps and potential for human error
- Increase the speed and volume of server retirement
- Decrease energy consumption and carbon emissions from data centers
- Create a scalable approach for ongoing infrastructure optimization

## Approach

- **Implementing automation with Autonomous Control Plane (ACP):** ACP automates data center infrastructure lifecycle management, ensuring SDP can scale operations in a safe, secure, predictable, and observable way. ACP executes continuous and incremental changes, enhancing trust by driving the safe and seamless removal of hosts from the network.
- **Process optimization:** reduced decommissioning manual steps by over 80%, freeing engineers for other critical projects.
- **Enhancing data management by disconnecting networks:** ACP automatically disconnects decommissioned servers from the production network prior to shutdown, eliminating lengthy manual procedures that are susceptible to human error.
- **Safety measures:** ACP’s built-in safety net—a five-day grace period—enabled the team to reverse the decommissioning process and swiftly reinstate hosts to the production VLAN if necessary.
- **Measuring Carbon Impact:** Conducted a detailed carbon impact analysis using Salesforce CRM Analytics dashboards and manually-computed data center metrics, comparing energy consumption and carbon emissions before and after automation to track progress against the baseline.

## Impact

- **Energy conservation:** saved 10,475 megawatt-hours of energy from April 2022 to July 2023, equivalent to powering 83 U.S. households for a year.
- **Carbon emissions reduction:** reduced 3,506 metric tons of carbon dioxide emissions, removing the need for 15,336 wooded acres to annually absorb that much CO2 from the environment.
- **Operational efficiency - increased decommissioning speed:** Automation increased the velocity of server decommissioning, leading to the faster powering off of energy-hungry machines.
- **Significant cost savings:** the automation effort saved approximately $900,000 in energy costs alone between April 2022 and July 2023, while also reducing labor costs by decreasing the manual decommissioning process from 16 steps to just 3 steps - an 80% reduction in required manual intervention.

## Key Takeaways

- **Embrace automation:** leveraging automation tools like ACP can drastically reduce manual intervention, improve efficiency, and enhance sustainability.
- **Regular monitoring:** continuous monitoring and analysis of carbon impact data are crucial for measuring progress and making data-driven decisions.
- **Prioritize sustainability:** the SDP team showed that sustainability initiatives can directly support IT's core objectives of cost reduction and operational efficiency. By retiring unnecessary servers, they simultaneously reduced carbon footprint and infrastructure maintenance burden, creating alignment between environmental and business goals.

## Future Steps

- Expand the automated decommissioning process to additional data centers across the global infrastructure.
- Develop more advanced predictive analytics to identify servers for decommissioning based on utilization patterns.
- Explore additional opportunities for energy efficiency in data center operations.
- Share best practices and methodologies with the broader tech industry to amplify environmental impact.
- Continue refining carbon impact measurement methodologies for greater accuracy.

## Conclusion

Salesforce’s Automated Server Decommissioning Program demonstrates the significant impact that automation can have on reducing carbon emissions and improving operational efficiency. This case study serves as a model for other companies aiming to achieve similar sustainability goals through innovative technology solutions.