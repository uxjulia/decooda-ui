---
layout: docs
title: Create Post
description: Example component for creating a post
group: decooda-components
toc: true
---
<div class="mb-3" style="max-width:50rem">
{% include decooda/create-post.html %}
</div>

{% highlight html %}
<div class="card">
  <div class="card-header bg-white d-inline-flex justify-content-between">
    <div>
      <span class="h5 text-uppercase font-weight-bold mr-3">Create a Post</span>
      <span class="h5 text-uppercase font-weight-light">
        Start a Conversation
      </span>
    </div>
    <i class="material-icons">more_vert</i>
  </div>
  <div class="card-body bg-light" id="toolbar">
    <div
      class="btn-toolbar text-secondary mb-1"
      role="toolbar"
      aria-label="Toolbar with button groups"
      >
      <div class="btn-group mr-2" role="group">
        <a role="button" class="btn btn-light">
          <i class="fas fa-bold fa-fw"></i>
        </a>
        <a role="button" class="btn btn-light">
          <i class="fas fa-italic fa-fw"></i>
        </a>
        <a role="button" class="btn btn-light">
          <i class="fas fa-underline fa-fw"></i>
        </a>
      </div>
      <div class="btn-group mr-2" role="group">
        <a role="button" class="btn btn-light">
          <i class="fas fa-list-ol fa-fw"></i>
        </a>
        <a role="button" class="btn btn-light">
          <i class="fas fa-list-ul fa-fw"></i>
        </a>
        <a role="button" class="btn btn-light">
          <i class="fas fa-align-left fa-fw"></i>
        </a>
      </div>
      <div class="btn-group" role="group">
        <a role="button" class="btn btn-light">
          <i class="fas fa-link fa-fw"></i>
        </a>
        <a role="button" class="btn btn-light">
          <i class="fas fa-paperclip fa-fw"></i>
        </a>
      </div>
    </div>
    <div class="form-group">
      <input class="form-control" placeholder="Subject Line Goes Here" />
    </div>
    <div class="form-group">
      <textarea class="form-control" rows="4"></textarea>
    </div>
    <div class="form-group">
      <div class="btn-group float-right">
        <button type="button" class="btn btn-primary rounded-0">Post</button>
        <button
          type="button"
          class="btn btn-primary dropdown-toggle dropdown-toggle-split"
          data-toggle="dropdown"
        >
          <span class="sr-only">Toggle Dropdown</span>
        </button>
        <div class="dropdown-menu dropdown-menu-right">
          <div class="form-group px-3 pt-3" style="width: 24rem;">
            <label class="text-primary" for="search">
              Select where you want to post
            </label>
            <div class="input-group input-group-sm mb-3">
              <div class="input-group-prepend">
                <span class="input-group-text bg-white" >
                  <i class="fas fa-search"></i>
                </span>
              </div>
              <input
                type="email"
                class="form-control"
                id="search"
                placeholder="Search for available groups"
              />
            </div>
            <div class="form-group form-check">
              <input type="checkbox" class="form-check-input" id="group1" />
              <label class="form-check-label" for="group1">Group Name</label>
            </div>
            <div class="form-group form-check">
              <input type="checkbox" class="form-check-input" id="group2" />
              <label class="form-check-label" for="group2">Group Name</label>
            </div>
            <div class="form-group form-check">
              <input
                type="checkbox"
                class="form-check-input"
                id="group3"
              />
              <label class="form-check-label" for="group3">Group Name</label>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
{% endhighlight %}

Add `.dropdown-menu-right` class to the `.dropdown-menu` to properly align the menu dropdown.

<div class="clearfix mb-3 mt-3" style="height: 170px">
  <div class="dropdown float-right">
    <button class="btn py-0 text-secondary" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
      <i class="fas fa-ellipsis-v"></i>
    </button>
    <div class="dropdown-menu dropdown-menu-right show" aria-labelledby="dropdownMenuButton">
      <button class="dropdown-item text-primary" type="button"><i class="fas fa-bookmark fa-fw text-secondary"></i> Bookmark Post</button>
      <button class="dropdown-item text-primary" type="button"><i class="fas fa-minus-square fa-fw text-secondary"></i> Unfollow Username</button>
      <button class="dropdown-item text-primary" type="button"><i class="fas fa-flag fa-fw text-secondary"></i> Report Post</button>
      <button class="dropdown-item text-primary" type="button"><i class="fas fa-bookmark fa-fw text-secondary"></i> Edit Filter Preferences</button>
    </div>
  </div>
</div>

{% highlight html %}
<div class="dropdown">
  <button class="btn py-0 text-secondary" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    <i class="fas fa-ellipsis-v"></i>
  </button>
  <div class="dropdown-menu dropdown-menu-right" aria-labelledby="dropdownMenuButton">
    <button class="dropdown-item text-primary" type="button"><i class="fas fa-bookmark fa-fw text-secondary"></i> Bookmark Post</button>
    <button class="dropdown-item text-primary" type="button"><i class="fas fa-minus-square fa-fw text-secondary"></i> Unfollow Username</button>
    <button class="dropdown-item text-primary" type="button"><i class="fas fa-flag fa-fw text-secondary"></i> Report Post</button>
    <button class="dropdown-item text-primary" type="button"><i class="fas fa-bookmark fa-fw text-secondary"></i> Edit Filter Preferences</button>
  </div>
</div>
{% endhighlight %}

The "Post" button in this example has had the default `border-radius` removed by adding Bootstrap's [border utility]({{ site.baseurl }}/docs/{{ site.docs_version }}/utilities/borders) class `.rounded-0` to the `.btn` classes.

The dropdown it triggers utilizes a `.form-group` class along with Bootstrap's [spacing utility]({{ site.baseurl }}/docs/{{ site.docs_version }}/utilities/spacing) classes (`.px-3`, `.pt-3`) and a custom width to achieve the custom dropdown look.

<div class="clearfix" style="height: 300px">
  <div class="btn-group float-right">
    <button type="button" class="btn btn-primary rounded-0">Post</button>
    <button
      type="button"
      class="btn btn-primary rounded-0 dropdown-toggle dropdown-toggle-split"
      data-toggle="dropdown"
    >
      <span class="sr-only">Toggle Dropdown</span>
    </button>
    <div class="dropdown-menu dropdown-menu-right show">
      <div class="form-group px-3 pt-3" style="width: 24rem;">
        <label class="text-primary" for="search"
        >Select where you want to post</label
        >
        <div class="input-group input-group-sm mb-3">
          <div class="input-group-prepend">
            <span class="input-group-text bg-white" >
              <i class="fas fa-search"></i>
            </span>
          </div>
          <input
            type="email"
            class="form-control"
            id="search"
            placeholder="Search for available groups"
          />
        </div>
        <div class="form-group form-check">
          <input type="checkbox" class="form-check-input" id="group1" />
          <label class="form-check-label" for="group1">Group Name</label>
        </div>
        <div class="form-group form-check">
          <input type="checkbox" class="form-check-input" id="group2" />
          <label class="form-check-label" for="group2">Group Name</label>
        </div>
        <div class="form-group form-check">
          <input
            type="checkbox"
            class="form-check-input"
            id="group3"
          /><label class="form-check-label" for="group3">Group Name</label>
        </div>
      </div>
    </div>
  </div>
</div>

<div>
{% highlight html %}
<div class="btn-group">
  <button type="button" class="btn btn-primary rounded-0">Post</button>
  <button
    type="button"
    class="btn btn-primary rounded-0 dropdown-toggle dropdown-toggle-split"
    data-toggle="dropdown"
  >
    <span class="sr-only">Toggle Dropdown</span>
  </button>
  <div class="dropdown-menu dropdown-menu-right">
    <div class="form-group px-3 pt-3" style="width: 24rem;">
     ...
    </div>
  </div>
</div>
{% endhighlight %}
</div>
