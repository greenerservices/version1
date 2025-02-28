---
homepage: false
layout: main
title: 8b. Develop efficient software
includeInBreadcrumbs: true
eleventyNavigation:
  key: 8b. Develop efficient software
  parent:  8. Develop and test for efficient engineering
---

Various approaches can be adopted to reduce the energy consumption of both the ‘front end’ (the user-facing part) and the ‘back end’ of a website or application.

## Lead Roles

<p class="govuk-body"><strong class="govuk-tag">
  Developer
</strong></p>

* * *

## Sub-actions

[8b.i Consider server side rendering](#(i)-consider-server-side-rendering)
[8b.ii Utilise lazy loading](#(ii)-utilise-lazy-loading)
[8b.iii Utilise caching where possible](#(iii)-utilise-caching-where-possible)

* * *

###  (i) Consider server side rendering

Server-side rendering (SSR) is a technique that involves rendering a web page on a server upfront before sending it to the user’s browser. This can save energy relative to client-side rendering (CSR), where the browser generates the content after receiving the raw data from the server.

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