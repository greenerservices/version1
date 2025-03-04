---
homepage: false
layout: main
title: 9c. Create an efficient testing approach
includeInBreadcrumbs: true
eleventyNavigation:
  key: 9c. Create an efficient testing approach
  parent:  9. Develop and test for efficiency
---

Efficient testing serves to reduce energy consumption.

### Likely Lead Roles

QA & Testing, Developer

* * *

## Sub-actions

[9c. (i) Adopt a shift-left testing approach ](#(i)-adopt-a-shift-left-testing-approach)
[9c. (ii) Make use of asynchronous testing](#(ii)-make-use-of-asynchronous-testing)
[9c. (iii) Optimise test scripts](#(iii)-optimise-test-scripts)
[9c. (iv) Consider server side rendering](#(i)-consider-server-side-rendering)
[9c. (v) Utilise lazy loading](#(ii)-utilise-lazy-loading)
[9c. (vi) Utilise caching where possible](#(iii)-utilise-caching-where-possible)

* * *

###  (i) Adopt a shift-left testing approach

Shift-Left (test earlier) is accepted good practice to avoid energy intensive rework and also Shift-Right (test in live environments) enables identification of runtime inefficiencies.

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