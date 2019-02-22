---
layout: docs
title:  Image Cards
description: Example of image card usage
group: decooda-components
toc: true
---

<div class="mb-3" style="max-width:30rem">
  {% include story.html %}
</div>

{% highlight html %}
<div class="card">
  <div class="card-header bg-white d-flex w-100 justify-content-between">
    <span class="initialism">TOP STORIES</span>
    <button class="btn text-muted m-n2"><i class="fas fa-ellipsis-v"></i></button>
  </div>
  <div class="card-body">
    <img src="/path/to/article/image.png" class="card-img-top rounded-0" alt="...">
    <!-- The first card is the largest, for the most prominent news story -->
    <div class="card-body">
      <div class="d-flex justify-content-between mb-2">
        <img src="/path/to/news/source-logo.png" alt="...">
        <i class="fas fa-external-link-square-alt text-muted"></i>
      </div>
      <h5 class="card-title">Article Headline</h5>
      <p class="text-muted small mb-1">March 31 at 7:23 am</p>
    </div>
     <!-- The following cards are smaller and less prominent -->
    <div class="d-flex justify-content-between">
      <div class="pr-0 mr-1">
        <img src="/path/to/article/image.png" class="card-img-top rounded-0" alt="...">
        <div class="card-body p-2">
          <div class="d-flex justify-content-between">
            <small>
              <p class="text-uppercase mb-1">XYZ News</p>
            </small>
            <i class="fas fa-external-link-square-alt text-muted"></i>
          </div>
          <p class="font-weight-bold">Article Headline</p>
          <p class="text-muted small mb-1">March 31 at 7:23 am</p>
        </div>
      </div>
      <div class="pr-0 ml-1">
        <img src="/path/to/article/image.png" class="card-img-top rounded-0" alt="...">
        <div class="card-body p-2">
          <div class="d-flex justify-content-between">
            <small><p class="text-uppercase mb-1">XYZ News</p></small>
            <i class="fas fa-external-link-square-alt text-muted"></i>
          </div>
          <p class="font-weight-bold">Article Headline</p>
          <p class="text-muted small mb-1">March 31 at 7:23 am</p>
        </div>
      </div>
    </div>
  </div>
  <div class="card-footer bg-white" style="min-height:35px;"></div>
</div>

{% endhighlight %}
