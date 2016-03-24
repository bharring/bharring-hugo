+++
date = "2015-12-08T11:12:50-06:00"
draft = true
title = "Welcome to Bradley's homepage"

+++

## Welcome

I created this site with [Hugo](https://gohugo.io/), a Go based static website generator, using the [Hugo-Uno theme](http://themes.gohugo.io/hugo-uno/). I hope to add more content about software, DIY projects, and travel photos soon.

Here's an embedded JavaScript chart comparing Hugo's compile times to other comparable frameworks. Go is very fast.  
{{% chart id="basicChart" width="860" height="400" js="../../js/chartData.js" %}}


Here's an example photo gallery of my favorite city to walk around in, Barcelona.
<ul style="list-style: none;" id="lightGallery">
    <li data-src="../../img/pathToImg.jpg">
        <img src="../../img/pathToThumb.jpg"></img>
    </li>
    <li data-src="../../img/pathToImg2.jpg">
        <img src="../../img/pathToThumb2.jpg"></img>
    </li>
</ul>

<script src=../../js/lightGallery.min.js></script>
<script>
    $("#lightGallery").lightGallery();
</script>
