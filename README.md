# Welcome to My Blog!

Sharing my thoughts, ideas, and projects. Check out the latest posts below:

## Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})  
  <small>Published on {{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}

---

Feel free to explore, leave a comment, or reach out to me!  
[Contact Me](contact.md)
