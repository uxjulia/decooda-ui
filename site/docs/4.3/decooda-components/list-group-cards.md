---
layout: docs
title: List Group Cards
description: Example of how cards are used to display list groups
group: decooda-components
toc: true
---
A custom card with three lines..
<div class="mb-3" style="max-width:24rem">
 {% include decooda/three-line-list.html %}
</div>

A custom card with two lines..
<div class="mb-3" style="max-width:24rem">
 {% include decooda/two-line-list.html %}
</div>

Add the `.list-group-flush` class to `.list-group` when placing a list-group within a card for proper rendering.

<div style="max-width:50rem">
{% highlight html %}
<div class="card">
  <div class="card-header bg-white d-flex w-100 justify-content-between">
    <span class="initialism">
     A Fancy Card Title
    </span>
    <button class="btn text-muted m-n2"><i class="fas fa-ellipsis-v"></i></button>
  </div>
  <ul class="list-group list-group-flush">
    <li class="list-group-item border-0">
      <div class="d-inline-flex w-100">
         <div class="mr-1 d-flex align-items-center">
           <img class="rounded-circle" src="/path/to/avatar.png" alt="...">
          </div>
        <div class="d-inline-flex flex-column align-items-start ml-3">
            <p class="mb-1">Username</p>
            <p class="text-muted small mb-1">Username Title</p>
        </div>
        <div class="d-flex mr-0 ml-auto align-items-center">
          <div class="d-flex mr-0 ml-auto align-items-center">
            <button class="btn btn-outline-primary">Some Button</button>
          </div>
        </div>
      </div>
    </li>
   </ul>
   <div class="card-footer bg-white" style="min-height:35px;"></div>
</div>
{% endhighlight %}
<div style="max-width:50rem">
