---
title: Google Lighthouse score
---

What is the 'Google score' in your portfolio exactly, you ask? The short answer is: it is a measurement from Google, that indicates the quality of a website.

To generate this score Google renders the website in Chrome. While doing so, Google analyzes the code and performance of your website in a series of audits. These audits are seperated into four categories: performance, accessibility, best practices and SEO. Each category scores between 0 and 100, where 100 is the best and 0 is the worst score. If you want to check the score or the audits yourself, you can do so at the [web.dev website](https://web.dev).

Note that on this website I use the average of these four categories as the 'Google score' for simplicity reasons.

## Performance

Lighthouse returns a Performance score between 0 and 100. 0 is the lowest possible score. 100 is the best possible score which represents the 98th percentile, a top-performing site. A score of 50 represents the 75th percentile. An important performance metric is the [Speed index](/blog/speed-index-explained/).

## Accessibility

The Accessibility score is a weighted average of all the accessibility audits. See Scoring Details for a full list of how each audit is weighted. The heavier-weighted audits have a bigger impact on your score. 

## Best practices

Lighthouse returns a Best Practices score between 0 and 100. 0 is the worst possible score, and 100 is the best. The Best Practices audits are equally weighted.

## SEO

Lighthouse returns a SEO score between 0 and 100. 0 is the worst possible score, and 100 is the best. A website with a high SEO score will end up higher in the search results than a website with a low SEO score.