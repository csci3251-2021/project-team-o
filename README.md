### Introduction

In this project, students of CSCI3251 will finally get the chance to have real hands on experience on collaborating with others via GitHub. There will be 8 issues to be resolved, and each student should take on one issue. I am doing issue #3!

### Code :technologist:

We are going to collaborate on GitHub and code using the C language!

{% highlight c %} {% include_relative code.c %} {% endhighlight %}

![Workflow](https://github.com/csci3251-2021/project-team-o/actions/workflows/c-cpp.yml/badge.svg)

### Contributors :family_man_woman_girl_boy:	


* umzr
* eunicek4632
* mku24
* Moira-Z
* gabrielliu2001

{% for contributor in site.stu %}
  ![]({{ contributor.image }})
  <h2>
    <a href="https://github.com/{{contributor.user}}">
     {{ contributor.user }} - {{ contributor.name }}
    </a>
  </h2>
  <p>{{ contributor.content | markdownify }}</p>
{% endfor %}


* more to come!
