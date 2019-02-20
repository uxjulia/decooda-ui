---
layout: docs
title: Comments
description: An example of comments
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
{% include comment.html %}
</div>

{% highlight html %}
<div class="card-body">
  <div class="d-inline-flex w-100">
    <img class="rounded-circle mr-1 align-self-start" src="..."  alt="...">
    <div class="d-inline-flex flex-column align-items-start justify-content-center ml-3">
      <span class="mb-1">
       <!-- Comment user -->
      </span>
      <p class="text-muted small mb-2">
       <!-- Comment date -->
      </p>
      <div class="p-3 comment bg-light rounded">
        <!-- Comment content -->
      </div>
    </div>
  </div>
</div>
{% endhighlight %}
