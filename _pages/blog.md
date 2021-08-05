---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
redirect_from:
  - /blog
---

{% include base_path %}

<head>
<style>
a.blog:link {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
a.blog:visited {
  color: #003CA4;
  background-color: transparent;
  text-decoration: underline;
  font-weight:bold;
}
</style>
</head>

Some notes

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/blog_stability.pdf">
An algorithmic hypothesis of differential neural stability in the brain
</a>
</p>

{: style="text-align: justify" }
There is a long-running debate in the neuroscience community about whether task-specific neural representations are stable after task learning or whether they drift in some null-space that does not affect task performance, and there is a large body of experimental support for both hypotheses in different brain regions and contexts.
In this short note, we consider how differences in neural stability between brain regions may reflect different algorithmic approaches to addressing the challenge of continual learning, drawing inspiration from both the machine learning literature on continual learning and the neuroscience literature on neural stability and memory consolidation.

<p style="padding-bottom:-12px; margin-bottom:-12px; padding-top:8px; margin-top:8px">
<a style="font-size:1.3em" class="blog" href="http://KrisJensen.github.io/files/bias_blog.pdf">
Bayesian correction of systematic reviewer bias
</a>
</p>

{: style="text-align: justify" }
We increasingly rely on large-scale conferences for distributing our research, and conference presentations are often considered a quality-stamp for early-career researchers.
Despite the importance this puts on fair selection processes, conference organizers unfortunately do not have unlimited resources for reviewing submissions.
This leads to stochasticity in the review outcome depending on whether a submission is assigned 'good' or 'bad' reviewers.
However, by considering a Bayesian model that takes into account interactions between reviewers sharing submissions, we can explicitly remove systematic deviations from the mean across reviewers when assessing the quality each submission.
