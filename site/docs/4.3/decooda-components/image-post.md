---
layout: docs
title: Image Post
description: An example of an image post
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
 {% include post.html content="This is an image post." image=true showDownload=true %}
</div>

Add the`.card-img-top` class to the image and `.rounded-0` to remove the border-radius.

{% highlight html %}
<div class="card">
  <div class="card-header">...</div>
  <div class="card-body">
     <!-- Post text -->
    <img src="..." class="card-img-top rounded-0" alt="...">
  </div>
  <div class="card-footer>
   <!-- Footer content -->
  </div>
</div>

{% endhighlight %}
