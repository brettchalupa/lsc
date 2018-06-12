---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

[logo]

[intro -- premise and schedule]

[some intro art -- maybe the colony and some characters? basically the promo art]

New to _Lunar Space Colony_?

{% assign first_post = site.posts.last %}
<a class="button" href="{{ first_post.url | relative_url }}">Start from the Beginning</a>

{% assign latest_post = site.posts.first %}
<a class="button" href="{{ latest_post.url | relative_url }}">Read the Latest Episode</a>

[any news and announcements]

[read on tapas/webtoon/RSS]
