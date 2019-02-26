---
layout: docs
title: Image Post
description: An example of an image post
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
 {% include decooda/post.html content="This is an image post." image=true showDownload=true %}
</div>

Add the`.card-img-top` and `.rounded-0` classes to the `<img>` so that it renders properly.

<div style="max-width:50rem">
{% highlight html %}
<div class="card">
  <div class="card-header">...</div>
  <div class="card-body">
    Some post content...
    <img src="/path/to/image.png" class="card-img-top rounded-0" alt="...">
  </div>
  <div class="card-footer">
    <button class="btn text-muted p-0">Show Comments <i class="fas fa-chevron-right text-muted mx-2"></i></button>
    <span class="text-muted">10 comments</span>
  </div>
</div>
{% endhighlight %}
</div>