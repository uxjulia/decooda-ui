---
layout: docs
title:  Image Cards
description: Example of image card usage
group: decooda-components
toc: true
---

<div class="mb-3" style="max-width:24rem">
  {% include story.html %}
</div>

{% highlight html %}
<div class="card">
  <div class="card-header bg-white d-flex w-100 justify-content-between">
    <span class="initialism">TOP STORIES</span>
    <button class="btn text-muted m-n2"><i class="fas fa-ellipsis-v"></i></button>
  </div>
  <div class="card rounded-0">
    <!-- Image -->
    <img src="..." class="card-img-top rounded-0" alt="...">
    <div class="card-body">
      <div class="d-flex justify-content-between mb-2">
        <span><!-- Insert news source logo here --></span>
        <i class="fas fa-external-link-square-alt text-muted"></i>
      </div>
      <h5 class="card-title">
        <!-- Article Title -->
      </h5>
      <p class="text-muted small mb-1">
        <!-- Date -->
      </p>
    </div>
  </div>
</div>

{% endhighlight %}
