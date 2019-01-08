---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: /images/LSC Cover Art.jpg
---

{% assign first_post = site.posts.last %}

<a href="{{ first_post.url | relative_url }}">
  <img src="/images/LSC Cover Art.jpg" alt="Bri and Toto in front of the Moon" class="lsc-cover">
</a>

<p>An incomplete sci-fi comic.</p>

<p>Bri, an engineer, starts a new life onboard a colony orbiting the Moon.</p>

<p><em><strong>Creator note:</strong> this project is abandoned, but the website will stay around as an archive.</em></p>

<p>New to <strong>Lunar Space Colony</strong>?</p>

<a class="button" href="{{ first_post.url | relative_url }}">Start from the Beginning</a>

{% assign latest_post = site.posts.first %}
<a class="button" href="{{ latest_post.url | relative_url }}">Read the Latest Episode</a>
