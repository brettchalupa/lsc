---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: /images/LSC Cover Art.jpg
---

<img src="/images/LSC Cover Art.jpg" alt="Bri and Toto in front of the Moon" class="lsc-cover">

<p>A weekly sci-fi comic. New episode every Tuesday.</p>

<p>Bri, an engineer, starts a new life onboard a colony orbiting the Moon.</p>

<p>New to <strong>Lunar Space Colony</strong>?</p>

{% assign first_post = site.posts.last %}
<a class="button" href="{{ first_post.url | relative_url }}">Start from the Beginning</a>

{% assign latest_post = site.posts.first %}
<a class="button" href="{{ latest_post.url | relative_url }}">Read the Latest Episode</a>
