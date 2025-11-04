---
layout: page
title: Tweets
subtitle: Find. Pay. Bring joy.
---

{% include image.html path="/assets/images/birb.png" width="33%" link="https://ants.sh/t/SecretSatsa" %}

### Feeling Generous?

Find invoices that sport the [#SecretSatsa](https://ants.sh/t/SecretSatsa) hashtag
and pay them!

<nostr-stream
  filters='[{"kinds":[1],"#t":["SecretSatsa"],"limit":21}]'
  relays='["wss://nfrelay.app", "wss://nos.lol", "wss://relay.nostr.band"]'
  theme="dark"
  display="card"
  limit="21">
</nostr-stream>
