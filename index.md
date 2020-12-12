# Welcome to my portfolio! 

### I'm glad that you found your way to my page. Here you can learn more [about me]({% link about.md %}).

This is the main page from which you can press any cathegory of interest to find out more about it. 

## Education
I am currently on my 4th year. Currently I am performing my master in which I combine (1) Software Intensive Systems with (2) Risk Management (Statistics). Some of the courses I have completed are (1) Software Development for Large Systems and Configuration management, (2) Stationary Stochastic Processes and Time Series Analysis. 

## Private projects
I have been doing some own projects too. Maybe I can interest you in a water pump for my tomatoes? Or how about some algorithms common CS-related problem written in [haskell]({% link _posts/2020-12-12-haskell-algorithms.md %})? Or would you rather want to see a website for register workouts? 

## Other 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
