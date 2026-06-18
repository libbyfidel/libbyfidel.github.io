---
title: Builder Test 2
nav_label: Builder Test 2
nav_order: 50
show_in_nav: true
custom_css: '* { box-sizing: border-box; } body {margin: 0;}#iosh{padding:3rem 2rem;}'
---
<body><section id="iosh"><h1>Builder Test 2</h1><p>Start building this page — drag blocks in from the left sidebar.</p></section><div class="blog-header"><span class="blog-title">Writing</span><span class="blog-subtitle">Essays &amp; thoughts</span></div><div class="posts">{% for post in site.posts %}<a href="{{ post.url | relative_url }}" class="post"><div class="post-date">{{ post.date | date: "%b %Y" }}</div><div><span class="post-tag">{{ post.tag | default: "Essay" }}</span><h2 class="post-title">{{ post.title }}</h2><p class="post-excerpt">{{ post.excerpt }}</p></div></a>{% endfor %}</div><p class="content-section-title">Contact</p><div class="contact-grid">{% for c in site.data.settings.contacts %}<div class="contact-item"><span class="contact-label">{{ c.label }}</span><a href="{{ c.url }}" class="contact-value" target="_blank">{{ c.value }}</a></div>{% endfor %}</div></body>