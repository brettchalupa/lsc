---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

[logo]

Bri, an engineer, starts a new life onboard a colony orbiting the Moon.

_A weekly sci-fi comic. New episode every Tuesday._

[some intro art -- maybe the colony and some characters? basically the promo art]

<p class="center">
  New to <strong>Lunar Space Colony</strong>?
</p>

{% assign first_post = site.posts.last %}
<a class="button" href="{{ first_post.url | relative_url }}">Start from the Beginning</a>

{% assign latest_post = site.posts.first %}
<a class="button" href="{{ latest_post.url | relative_url }}">Read the Latest Episode</a>

[read on tapas/webtoon/RSS]
