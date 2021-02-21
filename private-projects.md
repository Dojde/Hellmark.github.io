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
  - title: "Leader of Youth Handball Team"
    tags: 
    - Leadership
    - Volunteering
    - Teamwork
literature:
  - title: "Literature"
    tags: 
    - Learning, Knowledge
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
<span style="font-size: 16px; line-height: normal;">A web-based application where a user can register multiple types of workouts, set goals and view the progress. This project quickly became a very good platform for me to gain practical experience in web-programming, testing, continous integration, database design and much more. The backend is written in django and communicates with the client through an REST API. The client is built in react and is using hooks, redux and sagas. It is a work in progress but my ambition is to soon publish the website for you to view.</span>


{% include content_row id="water_pump" %}
<span style="font-size: 16px; line-height: normal;">A watering system for my plants at home. I used an esp as client which controlled the pump. In building this system I gained experience with soldering, relay cards, circut diagrams and much more. As a challenge I decided to implement the server side from scratch which included buliding an server with express.js which communicated with the esp through an mqtt broker, logged the values with InfluxDB, presented infomation with grafana and automated the watering with node-red.</span>

{% include content_row id="handball" %}
<span style="font-size: 16px; line-height: normal;">I have been responsible for a youth handball teams physical training. This was a role I held for over 4 years and had the luxuray to be a part of an incredibly competent group of coaches. With good structure, lots of engagement and many hours of hard work we became the largest team in our age category and managed to have all 3 of our teams to be a part of the last 32 teams standing in the Swedish Championship (which had never been done before). This engagement resulted in many hours of contemplating and learning about how I could best contribute to the development of the players. I took multiple courses, planned countless workout-sessions and developed a [website](https://hjhulugi.wordpress.com/) where the players could take part of my thoughts regarding exercise, sleep, nutriton and mental aspects.</span>

{% include content_row id="literature" %}
<span style="font-size: 16px; line-height: normal;">My favourite genre is non-fiction. I deeply appreciate a well-written book which manages to explain the underlying reason of why things are as they are and presents new perspectives on everyday things. Therefore, some of my favourite subjects are psychology and behavioral economics.</span>

{% include content_row id="haskell" %}
<span style="font-size: 16px; line-height: normal;">Haskell is a purely functional programming language. Learing haskell requires one to change the way of thinking about programming and adapt a new paradigm. I have used haskell to solve a few common CS-problems which can be found in [this repo](https://github.com/Dojde/haskell-algorithms.git). Currently, only a few problems displayed but I would argue that to be able to solve them in haskell requires quite a lot of effort.</span>
