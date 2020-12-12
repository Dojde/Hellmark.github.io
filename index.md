## Welcome to my portfolio! 

I'm glad that you found your way to my page. If you want to learn more [about me]({% link about.md %}).

Here you will be able to find examples of projects that I have performed. Just choose a categoroy of your intrest and enjoy! 

# [Education] 
I am currently on my 4th year. Currently I am doing my master in which I combine computer science and statistics. 

# [Private projects]



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
