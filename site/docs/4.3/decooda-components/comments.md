---
layout: docs
title: Comments
description: An example of comments
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
{% include decooda/comment.html %}
</div>

<div style="max-width:50rem">
{% highlight html %}
<div class="card-body">
  <div class="d-inline-flex w-100">
    <img class="rounded-circle mr-1 align-self-start" src="..."  alt="...">
    <div class="d-inline-flex flex-column align-items-start justify-content-center ml-3">
      <span class="mb-1">Username</span>
      <p class="text-muted small mb-2">April 1 at 9:35 am</p>
      <div class="p-3 comment bg-light rounded">
        This is a short comment.
      </div>
    </div>
  </div>
</div>
{% endhighlight %}
</div>
