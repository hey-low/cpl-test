---
layout: best-practice
title: "Optimize multimedia files"
order: 540
icon: /assets/climate-icons/Icon-Magie.svg
number: "29"

section: Design Frugally
chapter-tag: design-frugally

previous-page: use-multimedia-wisely
next-page: minimize-data-transfer


matter: |
  Large multimedia files take up more storage space and require more energy during data transfer.  This is because the bigger the file, the more data needs to be transferred, which consumes more energy. Additionally, data centers which store and manage these files require more electricity to operate and cool the servers. 
  In addition to the decisions made by designers or product managers about the use of multimedia, if it's been decided that media adds value, there are still ways to significantly reduce the file size of what's displayed.

do: |
  - Compress files to reduce size without a noticeable loss of quality

  - Use vector images (SVG) or illustrations

  - Use CSS, pictos, and icons (provided by web fonts or standard fonts) rather than GIF, PNG, JPEG, etc. If you can’t, consider WebP or Avif as better image options.

  - Resize images using a CMS or manually (not in the browser) to reduce their size and deliver them to the appropriate size for each device

  - Collaborate with the development team to implement an automatic optimization workflow upon upload that includes resizing, compressing, and converting images
  
  - Combine CSS files together to reduce the number of HTTP requests
  
  - [Set up ultra eco-mode](set-up-ultra-eco-mode)

success: |
  - 🧑💰 Efficient utilization of data centers and servers for greener operations
 
  - 🧑 Streamlined product performance, exemplified by faster load times
 
  - 💰 Optimization leading to reduced cloud expenditure

consider: |
  We recommend running tests on multiple devices and connection speeds to identify the right balance between quality and size reduction. This ensures that the initiative does not adversely affect the user experience, as it is possible to experience compatibility issues when testing on older browsers, devices, and operating systems.
  New practices and experiments, such as [Branch magazine](https://branch.climateaction.tech/), demonstrate how to optimize media. Branch changes its styling and images based on the cleanliness of the energy in the UK at any given moment.
---
