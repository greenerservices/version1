---
homepage: false
layout: main
title: 8b. Develop efficient software
includeInBreadcrumbs: true
eleventyNavigation:
  key: 8b. Develop efficient software
  parent:  8. Develop and test for efficient engineering
---

Sustainable design patterns help create application architecture that:

minimises idle resources
enhances efficiency
leverages shared infrastructure

## Lead Roles

<p class="govuk-body"><strong class="govuk-tag">
  Developer
</strong></p>

* * *

## Sub-actions

[8b.i Follow patterns for microservices](#(i)-consider-server-side-rendering)
[8b.ii Apply best practices for containers](#(ii)-utilise-lazy-loading)
[8b.iii Use autoscaling capabilities](#(iii)-utilise-caching-where-possible)
[8b.iv Prioritise open source and inner source where possible](#(i)-consider-server-side-rendering)
[8b.v Use caching](#(ii)-utilise-lazy-loading)
[8b.vi Design for asynchronous patterns and transactions](#(iii)-utilise-caching-where-possible)

* * *

###  (i) Follow patterns for microservices

A microservices architecture breaks applications into smaller, independent services. This helps us build composable and collaborative services, driven by events, commands and queries. 

Static site generation (SSG) can also be used to ‘pre-build’ webpages and eliminate the need for server-side processing.

{% from "govuk/components/details/macro.njk" import govukDetails %}

{{ govukDetails({
  summaryText: "Read more about server side rendering",
  text: "Some placeholder text"
}) }}
* * *

###  (ii) Utilise lazy loading

Lazy loading is a technique that delays the loading of resources until they are needed, such as when users scroll to them on a page, thereby saving data transfer and associated energy use. 

#### Environmental benefit: 
This sub-action is likely to level medium levels of environmental benefit.

{{ govukDetails({
  summaryText: "Read more about lazy loading",
  html: "

#### Current level of adoption

This sub-action is a new one to implement.  

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

### (iii) Utilise caching where possible

Caching is the process of storing a copy of data in a temporary location. Caching techniques can focus on the browser, Content Delivery Networks (CDN) and Application Programme Interfaces (API).

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}