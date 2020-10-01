---
title: Live | WPAFW
permalink: "/live"
layout: live
banner: Live
nav: false
nav-title: Live
nav-order: 9
---

<div class="title">

## WPAFW Live	

</div>




<div class="stream stream__main">
<div id="main-stream"></div>
<script src="https://embed.twitch.tv/embed/v1.js"></script>
<script type="text/javascript">
  new Twitch.Embed("main-stream", {
  	width: "100%",
  	height: "100%",
    channel: "wpafw",
    layout: "video-with-chat",
    theme: "dark"
  });
</script>
</div>

<hr>

<div class="columns has-text-centered">
<div class="column is-4">
<div class="stream stream__charity">
<div id="charity-stream"></div>
<script src="https://embed.twitch.tv/embed/v1.js"></script>
<script type="text/javascript">
  new Twitch.Embed("charity-stream", {
  	width: "100%",
  	height: "100%",
    channel: "wpafwcandle",
    layout: "video",
    theme: "dark"
  });
</script>
</div>
</div>
<div class="column is-8">

<div class="subtitle">

## Donations

</div>

Donation list goes here.

<br>
<a class="button is-success button__breather" href="https://www.paypal.com/donate/?cmd=_s-xclick&hosted_button_id=YTNPGERSHSKVG&source=url" target="_blank">
<strong>Donate</strong>
<i class="fas fa-donate"></i>
</a>

</div>
</div>



Donations directly support our charity, [The Awesome Spirit of Wildlife](https://tasow.org/).