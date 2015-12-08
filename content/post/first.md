+++
date = "2015-12-08T11:12:50-06:00"
draft = true
title = "first"

+++

## A headline

Some Content

{{% chart id="basicChart" width="860" height="400" js="../../js/chartData.js" %}}


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
