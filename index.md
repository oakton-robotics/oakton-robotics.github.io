---
permalink: /
title: Home
layout: dashboard
---

### Welcome to the {{ site.data.year.name}} Team!

We build robots for blood sweat and glory, read more about us  [here](/about/).

<div class="row">
<div class="col-xs-5" markdown="1">

#### Quick links
- New software members  please read the [guide](oakton-robotics.gitbook.io) for answers to common questions.

</div>
<div class="col-xs-7" markdown="1">
#### Upcoming events
<div id ="upcoming" class="list-group" style="font-size:80%;overflow:auto; height:240px;" >
<ul><li class="list-group-item"><i>Loading...</i></li></ul>     
</div>
</div>
</div>

[//]: # (<!  include schedule.html current_only=true ->)


#### Meet the team
{% include gallery.html %}


<script src="/_assets/gcal.js"></script>

<div class="footer">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">


<p style="color: white; font-size: 100%; text-align:center;">
Follow Us!
<a href="https://www.facebook.com/Oaktobotics/" class="fa fa-facebook"></a>
<a href="https://twitter.com/oaktobotics" class="fa fa-twitter"></a>
</p>

<p style="font-size: 65%; text-align:center;">
<i>{{ site.data.year.name }} &middot; Site generated {{ "now" | date: "%Y-%m-%d %H:%M" }}</i>
</p>

</div> 
