---
layout: docs
title: Media Post
description: An example of a post with some media attachment
group: decooda-components
toc: true
---
 {% capture media-content %}
    {% include media-post.html title="This is a title" description="This is some description of the media that was uploaded" link="http://www.somelink.com" %}
{% endcapture %}
<div class="mb-3" style="max-width:50rem">
  {% include post.html content="This is a post with an attachment or upload." media=media-content showDownload=true %}
</div>

Add the`.card-img-top` class to the image and `.rounded-0` to remove the border-radius.

{% highlight html %}
<div class="card-body">
  <div class="card d-flex-inline flex-row w-100" style="border-width: 2px;">
    <div style="height:100%; max-width: 35%;">
      <!-- The media image / preview -->
      <img src="..." class="card-img-top rounded-0" alt="...">
    </div>
    <div class="card-body d-flex flex-column justify-content-between">
       <!-- Media title, description, etc. -->
    </div>
  </div>
</div>

{% endhighlight %}
