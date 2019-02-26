---
layout: docs
title: Comments
description: Examples of comments
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
{% include decooda/comment.html %}
</div>

<div style="max-width:50rem">
{% highlight html %}
<div class="card-body">
  <div class="d-inline-flex">
    <img class="rounded-circle mr-1 align-self-start" src="/path/to/avatar.png"  alt="...">
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

<hr/>

An example of a [text post]({{ site.baseurl }}/docs/{{ site.docs_version }}/decooda-components/text-post/) with a comment input field.

<div class="mt-3 mb-3">
  {% include decooda/post.html content="This is how a post would look like if a user was signed in and allowed to post comments." allowComments=true %}
</div>

{% highlight html %}
<div class="card-body bg-light">
  <div class="d-flex flex-row justify-content-between align-items-center">
    <img class="rounded-circle" src="/path/to/avatar.png" alt="...">
    <input class="form-control ml-2 mr-2"/>
    <button class="btn btn-primary">Comment</button>
  </div>
</div>
{% endhighlight %}

<hr/>

An example of a text post with comments.

<div class="mt-3 mb-3">
{% include decooda/post.html content="This is a an example of a text post with comments at the end. The comment box has a maximum height and causes the comments to scroll." showComments=true %}
</div>

