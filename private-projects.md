---
permalink: /projects/
layout: single
class: wide
author_profile: true
log_my_exercise: 
  - title: "LogMyExercises"
    tags: 
    - Programming
    - Full Stack Developer 
    - React
    - Sql
    - Django
water_pump: 
  - title: "Water Pump"
    tags: 
    - Node-Red
    - Grafana
    - Influxdb
    - Mqtt
handball:
  - title: "Youth Handball Team"
    tags: 
    - Leadership
    - Volunteering
    - Teamwork
literature:
  - title: "Literature"
    tags: 
    - Learning, knowledge
haskell:
  - title: "Algorithms in Haskell"
    tags: 
    - Functional Programming

---
<div style="text-align:center; margin-top:20px">
  <p style="font-size:36px; font-style:italic;">"Skill comes from consistent and deliberate practice."</p>
</div>
<p style="font-size: 18px;">On this page follows samples of private projects through which I have developed my skills.</p>

{% include content_row id="log_my_exercise" %}
<span style="font-size: 16px; line-height: normal;">I love to practice multiple different types of sports, but have not found a tool which allows me to register all my workouts in one place. So I decided to build my own. This quickly became a very good platform for me to gain practical experience in web-programming, testing, continous integration and many more aspects of software development. The backend is written in django and communicates with the client through an REST API. The client is built in react and is using both hooks, redux and sagas. It is a work in progress but my ambision is to soon publish the website for you to view.</span>

  
{% include content_row id="water_pump" %}
<span style="font-size: 16px; line-height: normal;">Since I got tired of giving water to my tomatoes and since they limited the amount of time one could spend away from home i decided to build a watering system for my plants. I used an esp as client which controlled the pump and gained in building this system I gained experience with soldering, relay cards, circut diagrams and much more. As a challenge I decided to implement the server side from scratch which included buliding an server with express which communicated with the esp through an mqtt broker, logged the values with InfluxDB, presented infomation with grafana and automated the watering with node-red.</span>

{% include content_row id="handball" %}
<span style="font-size: 16px; line-height: normal;">Through my youth I was a engaged in both the local handball and fotball team. Later, I returned to handball in the role of responsible for a youth teams physical training. This was a role I held for over 4 years and had the luxuray to be a part of an incredibly competent group of coaches. With good structure, lots of engagement and many hours of ward work we became the largest team in our age category and managed to have all 3 of our teams to be a part of the last 32 teams standing in the Swedish Championship. Something which had never been done before. This engagement resulted in many hours of contemplating and learning about how I could best contribute to the development of the players. I took multiple courses, planned countless workout-sessions and developed a website (https://hjhulugi.wordpress.com/) where the players could take part of my thoughts regarding exercise, sleep, nutriton and mental aspects.</span>

{% include content_row id="literature" %}
<span style="font-size: 16px; line-height: normal;">My favourite genre is non-fiction. I deeply appreciate a well-written book which manages to explain the underlying reason of why things are as they are and presents new perspectives on everyday things. Therefore, some of my favourite subjects to read about in my sparetime have been psychology and behavioral economics.</span>

{% include content_row id="haskell" %}
<span style="font-size: 16px; line-height: normal;">Haskell is a purely functional programming language. Learing haskell requires one to change the way of thinking about programming and adapt a new paradigm. I have used haskell to solve a few common CS-problems which can be found in [this repo](https://github.com/Dojde/haskell-algorithms.git). Currently, only a few problems displayed but I would argue that to be able to solve them in haskell requires quite a lot of effort.</span>
