---
layout: default
title: Ibrahim Awwal
description: This is my site. Welcome.
keywords: github pages, Jekyll, foundation 5
---

<div class="row">
    <div class="medium-3 columns" style="height: 200px; padding: 0px"><img src="headshot.jpg" alt="Ibrahim Awwal"/></div>
    <div class="medium-9 column">

        <p class="mbm">I'm an engineer and cofounder at <a href="https://gradescope.com">Gradescope</a>. I completed my Master's in the <a href="http://ece.ucsd.edu">ECE department</a> at UCSD, majoring in Intelligent Systems. While there, I worked on <a href="http://seelab.ucsd.edu/">mobile devices</a>, educational technology, and neural engineering. I am generally interested in applying machine learning to challenging engineering problems. In my undergraduate career I worked in <a href="http://cs.berkeley.edu/~pabbeel/">Pieter Abbeel's</a> Robot Learning Lab.
        </p>
    </div>
</div>

<div class="row">
    <div class="medium-9 column">

        <p class="mbm">I'm passionate about education, both learning as well as teaching. I have studied a broad variety of topics under the umbrellas of electrical engineering and computer science. I also taught the introductory signal processing (EE20) and circuits (EE40) courses at Berkeley. I was fortunate enough to work on the <a href="https://github.com/edx/edx-platform/commits?author=ibrahima">initial development</a> of the <a href="https://www.edx.org">EdX</a> discussion forums for its launch in fall 2012.</p>
    </div>

    <div class="medium-3 columns" style="height: 200px; padding: 0px"><a href="pictures/sunset.jpg"><img src="thumbs/sunset.png" /></a></div>
</div>


<div class="row">

    <div class="large-4 columns">
    <p>I enjoy exploring the beauty of nature, and capturing it with photography. I've also recently picked up distance running, though I'm far from a marathon runner (maybe someday!). Currently I'm aiming to run a half marathon in summer 2015.</p>
    </div>

    <div class="large-4 columns">
        <p>I do some hobbyist web development on the side. Web technologies these days have a very low barrier to entry, which makes it easy to pick up and do something interesting in a short span of time. And the evolution in this space is rapid so there's always something new to learn!</p>
    </div>

    <div class="large-4 columns">
        <h3>Posts</h3>
        <ul>
        {% for post in site.posts %}
            <li>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </li>
        {% endfor %}
        </ul>
    </div>

</div>
