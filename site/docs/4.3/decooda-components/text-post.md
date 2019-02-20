---
layout: docs
title: Text Post
description: An example of a text post
group: decooda-components
redirect_from: "/docs/4.3/decooda-components/"
toc: true
---
<div class="mb-3" style="max-width:50rem">
  {% include post.html content="This is the preview or main content area of the post. User experience product management metrics sales gen-z. Monetization business plan termsheet equity twitter direct mailing virality learning curve pivot. Success stock user experience advisor ramen value gamification research & development" %}
</div>
          
{% highlight html %}
<div class="card">
  <div class="card-header bg-white d-flex w-100 justify-content-between">
    <div class="d-inline-flex w-100">
      <div class="mr-1 d-flex align-items-center">
        <!-- User avatar goes here  -->
        <img class="rounded-circle" src="..." alt="...">
      </div>
      <div class="d-inline-flex flex-column align-items-start justify-content-center ml-3">
        <div>
          <!-- Markup for a user posting to a group -->
          <span class="mb-1">Username Text</span>
          <i class="fas fa-chevron-right mx-2 text-muted"></i>
          <span class="text-primary">Group Name</span>
        </div>
        <p class="text-muted small mb-1">
          <!-- Date of the post goes here -->
        </p>
      </div>
    </div>
    <button class="btn text-muted m-0 py-0"><i class="fas fa-ellipsis-v"></i></button>
  </div>
  <div class="card-body">
     <!-- Content of post goes here -->
  </div>
 <div class="card-footer bg-white d-flex align-items-center justify-content-between">
    <button class="btn text-muted p-0">Show Comments <i class="fas fa-chevron-right text-muted mx-2"></i></button>
    <span class="text-muted">10 comments</span>
  </div>
</div>
{% endhighlight %}
