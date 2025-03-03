---
homepage: false
layout: main
title: 8b. Use sustainable design patterns
includeInBreadcrumbs: true
eleventyNavigation:
  key: 8b. Use sustainable design patterns
  parent:  8. Design for greener architecture, data and security
---

Sustainable design patterns help create application architecture that:

• minimises idle resources
• enhances efficiency
• leverages shared infrastructure

### Likely lead roles

Technical architect

## Sub-actions

[8b.(i) Follow patterns for microservices](#(i)-follow-patterns-for-microservices)
[8b.(ii) Apply best practices for containers](#(ii)-apply-best-practices-for-containers)
[8b.(iii) Use autoscaling capabilities](#(iii)-use-autoscaling-capabilities)
[8b.(iv) Prioritise open source and inner source where possible](#(iv)-consider-server-side-rendering)
[8b.(v) Use caching](#(ii)-utilise-lazy-loading)
[8b.(vi) Design for asynchronous patterns and transactions](#(iii)-utilise-caching-where-possible)

* * *

###  (i) Follow patterns for microservices

A microservices architecture breaks applications into smaller, independent services. This helps us build composable and collaborative services, driven by events, commands and queries. 

#### Environmental benefit: 
<p class="govuk-body"><strong class="govuk-tag">
  Efficiency
</strong></p>

{% from "govuk/components/details/macro.njk" import govukDetails %}

{{ govukDetails({
  summaryText: "Read more",
  html: "

#### Likely environmental impact: medium

This sub-action is likely to be of medium environmental impact.

#### Current adoption level: medium

This sub-action being implemented on some projects across government.

***
  
#### Co-benefits

• User experience: Lazy loading can improve initial page loading times and optimise memory usage, especially for applications with large datasets. 

#### Trade-offs
 
• Number of requests: Lazy loading may mean the browser has to send multiple requests to the server for content as some users interact with a page. 
• Development time: It may also mean additional code needs to be added to instruct the browser how to lazy load. 

#### Implementation

Guidance on implementing lazy loading:
[https://cloudinary.com/guides/automatic-image-cropping/server-side-rendering-benefits-use-cases-and-best-practices](https://cloudinary.com/guides/automatic-image-cropping/server-side-rendering-benefits-use-cases-and-best-practices)

#### Further reading 

[https://www.cloudflare.com/en-gb/learning/performance/what-is-lazy-loading/](https://www.cloudflare.com/en-gb/learning/performance/what-is-lazy-loading/)

"
}) }}

***

###  (ii) Apply best practices for containers

Containarized architecture means packaging software into self-contained units. These can then consistently run in any environment.

#### Environmental benefit: 
Containerization helps ensure that services only consume necessary resources.
<p class="govuk-body"><strong class="govuk-tag">
  Efficiency
</strong></p>

{{ govukDetails({
  summaryText: "Read more",
  html: "

#### Likely environmental impact: medium

This sub-action is likely to be of medium environmental impact.

#### Current adoption level: medium

This sub-action being implemented on some projects across government.

***
  
#### Co-benefits

User experience: Lazy loading can improve initial page loading times and optimise memory usage, especially for applications with large datasets. 

#### Trade-offs
 
Number of requests: Lazy loading may mean the browser has to send multiple requests to the server for content as some users interact with a page. 
Development time: It may also mean additional code needs to be added to instruct the browser how to lazy load. 

#### Implementation

Guidance on implementing lazy loading:
[https://cloudinary.com/guides/automatic-image-cropping/server-side-rendering-benefits-use-cases-and-best-practices](https://cloudinary.com/guides/automatic-image-cropping/server-side-rendering-benefits-use-cases-and-best-practices)

#### Further reading 

[https://www.cloudflare.com/en-gb/learning/performance/what-is-lazy-loading/](https://www.cloudflare.com/en-gb/learning/performance/what-is-lazy-loading/)

"
}) }}

* * *

### (iii) Use autoscaling capabilities

Autoscaling is about adjusting the resources allocated to a workload based on demand.

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}

* * *

### (iv) Use open and inner source where possible

Open source is software where the source is publicly available. This allows anyone to access, change and distribute it.
Organisations use inner source to apply open source practices internally.

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}

* * *

### (v) Use caching

Caching temporarily stores frequently accessed data in a designated area (called a "cache"). This enables faster access to that data.

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}

* * *

### (vi) Encourage asynchronous patterns and transactions

Asynchronous patterns and transactions allow tasks to run independently of one-another. 

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}