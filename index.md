# Welcome to my portfolio! 

I'm glad that you found your way to my page. Here you will be able to find examples of projects that I have performed.

Is the introduction of me too breif? Learn more [about me]({% link about.md %}).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
