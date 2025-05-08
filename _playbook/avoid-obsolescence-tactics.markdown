---
layout: best-practice
title: "Avoid obsolescence tactics"
order: 550
icon: /assets/climate-icons/Icon-Obsolescence.svg
number: "23"

section: Discover Mindfully
chapter-tag: discover-mindfully

previous-page: prioritize-a-mobile-first-approach
next-page: reuse-and-recycle


matter: |
  Manufacturing end-user devices such as smartphones, computers, tablets, etc. accounts for 40% of global digital greenhouse gas emissions (GHG). It is the single largest source of emissions (the next biggest source is the usage of these end-user devices, estimated at 26%). It’s fairly simple: We must do everything we can to mitigate the desire to purchase new devices (smartphones, computers, tablets, etc.) by ensuring that digital products can function on as many existing devices as possible.

do: |
  - Understand current devices used by target users [Validate the user journey and needs](validate-the-user-journey-and-needs).

  - Evaluate how your product features affect device usage for both users and your internal teams. Are your features pushing users to upgrade their devices? Are you supporting older hardware, or unintentionally excluding them? Understanding this helps you reduce e-waste and extend device lifespans.

  - Give preference to standard and proven technologies, ideally open source (more in[Reuse and recycle](reuse-and-recycle)).

  - Design software for backward compatibility with older devices and operating systems.

  - Choose PWAs (Progressive Web Apps), usable both on mobile and desktop, instead of Native Apps (which usually require the latest OS and newer devices). It helps in reducing data storage, physical infrastructure, and data transmission. It also streamlines the design, development, and testing processes.

  - Be mindful of obsolescence tactics (hardware limitations, software updates) and avoid deceptive patterns (upgrade pop-ups, feature gating).

  - Extend product lifecycles through software updates.

  - Educate users on best practices to extend devices’ lifespan.

  - If you manage equipment, ensure that it is repairable and upgradable. If you don’t, [Influence your value chain and partners](influence-your-value-chain-and-partners) to promote best practices from the circular economy.

  - Build with a [progressive enhancement lens](https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement) rather than a graceful degradation lens.
    - Build for the most basic browser and develop advanced functionalities that can automatically render in browsers that support them. This ensures inclusivity, reduces device strain, and minimizes environmental impact—without compromising usability.

  - [Extending the lifetime of a device](https://learn.greensoftware.foundation/hardware-efficiency) has the effect of amortizing the carbon emitted so that its CO2e/year is reduced.
    - For end-user devices, **extending the lifespan** of  hardware reduces emissions.
    - For cloud computing, **increasing device utilization** reduces waste (although emissions are the same). The embodied carbon is much lower if utilization is higher. This is a benefit of public computing - you can scale as needed, with less waste.

success: |
  - 🧑💰 Measures to extend the longevity of hardware, reducing e-waste

  - 🌍 Active steps to minimize Electrical and Electronic Equipment Waste

  - 🧑💰 Enhanced user experience leading to improved conversion rates and overall satisfaction

consider: |
  You have three main types of obsolescence that you can have an impact on:

  1. **Hardware Obsolescence:** There are two types: 
    1. Technical, which occurs when new technologies make older devices outdated
    2. Functional, which happens when hardware no longer meets users' needs due to changes in technology or requirements.
  2. **Software Obsolescence:** Planned obsolescence is when companies intentionally design software to become obsolete, forcing users to purchase upgrades or new products. Compatibility obsolescence occurs when software is no longer compatible with older hardware or operating systems, requiring users to upgrade their devices to continue using the latest software.
  3. **Psychological Obsolescence:** Perceived obsolescence refers to the belief that a product is no longer fashionable or desirable, while social obsolescence is driven by peer pressure and social trends that influence individuals to replace their products with newer ones to fit in or maintain a certain image.
  Unplanned obsolescence is more common and hard to avoid. It describes the unintended outcome of forcing users to adopt the latest and greatest devices in order to run your product. Users no longer need a new device to get software upgrades. You can mitigate unplanned obsolescence with progressive enhancement, rather than “graceful degradation”, to deal with older devices.
---