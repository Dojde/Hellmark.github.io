# Welcome to my portfolio! 

I'm glad that you found your way to my page. Here you will be able to find examples of projects that I have performed and learn more about me.

More information about me can be found here {{ site.baseurl }}{% link about.md %}.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
