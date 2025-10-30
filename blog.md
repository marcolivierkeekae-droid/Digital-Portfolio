{% include background.html %}

<h1>My Blog</h1>
<p>Welcome to my blog! Here I share reflections, learning experiences, and project updates.</p>

<!-- Blog Posts List -->
<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %-d, %Y" }}
  </li>
  {% endfor %}
</ul>

<!-- Example Static Post (if no _posts yet) -->
<h2>Example Post: My First Blog</h2>
<p>Starting university was a major shift in my life. I had to learn time management, develop study habits, and embrace a growth mindset.</p>
[← Back to Home]({{ site.baseurl }}/index.html)

<script src="https://cdn.jsdelivr.net/npm/particles.js"></script>
<script>
particlesJS("particles-js", {
  "particles": {
    "number": {"value": 80},
    "size": {"value": 3},
    "move": {"speed": 1},
    "line_linked": {"enable": true, "color": "#00ffff"},
    "color": {"value": "#00ffff"}
  }
});
</script>

