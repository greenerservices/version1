---
homepage: false
layout: main
title: 9a. Consider choice of coding languages and frameworks
includeInBreadcrumbs: true
eleventyNavigation:
  key: 9a. Consider choice of coding languages and frameworks
  parent:  9. Develop and test for efficiency
---

The choice of languages and frameworks can impact efficiency and consumption. 

### Likely Lead Roles

Developer

* * *

## Sub-actions

[9a. (i) Use energy-efficient languages, where appropriate](#(i)-consider-server-side-rendering)
[9a. (ii) Use lightweight frameworks](#(ii)-utilise-lazy-loading)
[9a. (iii) Consider benefits of low code/no code](#(iii)-utilise-caching-where-possible)

* * *

###  (i) Use energy-efficient languages, where appropriate

There are differences between the energy consumption of programming languages. Consider:

memory usage and speed
if the language is a ‘compiled’ one

#### Environmental benefit: 
This sub-action is likely to level medium levels of environmental benefit.

{% from "govuk/components/details/macro.njk" import govukDetails %}

{{ govukDetails({
  summaryText: "Read more about server side rendering",
  text: "Some placeholder text"
}) }}
* * *

###  (ii) Use lightweight frameworks

Lazy loading is a technique that delays the loading of resources until they are needed, such as when users scroll to them on a page, thereby saving data transfer and associated energy use. 

#### Environmental benefit: 
This sub-action is likely to level medium levels of environmental benefit.

{{ govukDetails({
  summaryText: "Read more about lazy loading",
  html: "some placeholder"
}) }}

* * *

### (iii) Consider benefits of low code/no code

Caching is the process of storing a copy of data in a temporary location. Caching techniques can focus on the browser, Content Delivery Networks (CDN) and Application Programme Interfaces (API).

{{ govukDetails({
  summaryText: "Read more about caching"
}) }}