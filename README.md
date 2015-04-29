Web Development Starter Kit
===========================

This is a collection of resources that has helped web developers at
Prezi to become great and happy developers. It's a curated list of
books, articles and tutorials. It's based on the current technology
stack that we use at Prezi but it's useful for every full stack
developer.

## Introductory topics

- Learn data structures and algorithms. Data structures and algorithms
for programmers are like notes and scales for a musician. All
programming is built around data structures and algorithms. Whether
making the right choices when solving problems, will be determined by
your confidence in the basics.
    - **book: [The Algorithm Design Manual][data_struct]**
    - article: [Data Structures Succinctly: Part 1][datastructspart1]
- Learn Unix tools. Unix's philosophy of building simple, small,
modular tools is highly regarded for a reason. Problems that
seem complex usually can be solved with one liners in no time. Also
since most of today's infrastructures are built upon Un*x systems, a
great engineer might want to take advantage of being able to control
and hence own the full stack what they develop.
    - **book: [The Unix Programming Environment][unix_book]**
    - tutorial: [Unix tutorial][unix_tutorial]
- Learn version controlling. Version controlling is the alpha of
  today's development work flow. It's the breath of all open source
  projects, it helps teams collaborate day to day on their work and
  even for a single engineer working alone helps create the right
  mindset of working in baby steps and gives reassurance with the knowledge
  that you are able to go back to any previous state of the code base.
    - **tutorial: [Git tutorial][git_school] (time investment: 15 min)**
- Learn regular expressions. It's hard to bypass regular
  expressions. They are an impressive tool available in most
  languages to work with text.
    - **tutorial: [RegExp tutorial][regex_tutorial]**
- Understand how HTTP and browsers work. These technologies are on the
  lowest level of the Maslow pyramid of web development.
    - **article: [How Browsers Work: Behind the scenes of modern web browsers][browserswork]**
    - **article: [HTTP: The Protocol Every Web Developer Must Know][http_tutorial]**
    - **article: [website cookies][cookies]**

## Backend technologies

- We love beautiful code. Python's coding style (PEP 8) is a great
  tool to ensure a common coding style across teams.
    - **article: [PEP 8][pep8] (time investment: 2 hours)**
    - **article: [PEP 20 aka The Zen of Python][pep20] (time investment: 2 min)**
- Learn about Python virtual environments (virtualenv) in order to
  keep your local development environment sane.
    - **tutorial: [A non-magical introduction to Pip and Virtualenv for Python beginners][virtualenv] (time investment: 15 min)**
- Write a Django app from scratch. Django is a great web framework
  written in Python that we use for most of our web services. Learning
  the fundamantals of a web framework gives you the ability to write
  maintainable and scalable web sites and services in a fun and fast
  way.
    - **tutorial: [official Django tutorial][django_tutorial]**
    - book: [Two Scoops of Django: Best Practices For Django 1.6][scoops_of_django]
- We &#65533; Unicode. Learn how to enable internationalization and
  localization in a web application to give you the best experience
  for your users.
    - **article: [Internationalization and localization][i18n]**
- Learn Chef. We believe in full stack ownership. For that, being able
  to maintain your own infrastructure is essential. Chef is a great
  configuration management tool that lets you manage infrastructure as
  code.
    - tutorial: [Chef course][chef_tutorial]
- Learn to use the Python debugger. Even the best engineers make mistakes. The
  era of `print` statements is over.
    - **article: [PDB][python_debugger]**
- Learn about databases.
    - **tutorial: [Introduction to Databases][dbintro]**
- Launch your app on the cloud. Platform as a service is here. Now
  that you wrote your app in Django and manage the infrastructure with
  Chef, it shouldn't be hard, right?
    - **tutorial: [Getting Started with Django on Heroku][paas_tutorial]**
- Have a good Python IDE installed. Find your best friend.
    - Prezi engineers recommend using [PyCharm][pycharm]

## Frontend technologies

- Learn HTML and CSS. Writing semantic, clean markup is the backbone
  of your website or application. Mastering stylesheets will help
  express your content in a beautiful way.
    - **book: [Dive into HTML5][html5_book]**
    - **tutorial: [CSS tutorial][css_tutorial]**
    - **tutorial: [CSS Bootstrap tutorial][bootstrap]**
    - article: [CSS guidelines][css_guidelines]
    - tutorial: [LESS framework][less]
- Learn JavaScript. JavaScript is the assembly language of the web.
    - **book: [Eloquent JavaScript: A Modern Introduction to Programming][javascript_eloquent] (if you are new to programming)**
    - **book: [JavasCript: Good Parts][javascript_goodparts]:**
    - tutorial: [learn JavaScript properly][javascript_properly] (time investment: 8 week)
- Learn a JavaScript framework. Understanding the language is highly
  recommended and mastering a framework gives you the ability to be
  even more powerful.
    - article: [learn backbone.js completely][backbonejs]
- Set up your development environment. Make debug tools your friend
  and create an environment that lets you test across various browsers.
    - article: [devtools][devtools]
    - article: [Microsoft IE App Compat virtual machines][ievms]

## Advanced topics
- Write clean code. Great engineers write clean code to create
  maintainable systems.
    - **book: [Clean code][clean_code]**
    - book: [Clean Coder][clean_coder]
- Learn about modern software development process. Make continuous
  delivery, test driven development, and acceptance testing part of
  your everyday development tools.
    - **book: [Continuous Delivery][continuous_delivery]**
    - **book: [TDD by example][tddbook]**
    - video: [lecture #1 of Udacity Software Testing][tdd_udacity] about unit testing with coding exercises
    - **book: [The Cucumber Book][cucumber_book]**
    - video: [Top 5 Cucumber best practices][top5cucumber]
- Learn about web application security principles.
    - article: [ Web Application Exploits and Defenses][webappsecurity]


[data_struct]: http://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693
[unix_book]: http://www.amazon.com/Unix-Programming-Environment-Prentice-Hall-Software/dp/013937681X/ref=sr_1_16?...
[unix_tutorial]: http://www.learnshell.org/
[git_school]: https://try.github.io/levels/1/challenges/1
[regex_tutorial]: http://regexone.com/lesson/
[browserswork]: http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/
[http_tutorial]: http://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177
[pep8]: http://legacy.python.org/dev/peps/pep-0008/
[django_tutorial]: https://docs.djangoproject.com/en/1.7/intro/tutorial01/
[scoops_of_django]: http://twoscoopspress.org/products/two-scoops-of-django-1-6
[i18n]: https://docs.djangoproject.com/en/dev/topics/i18n
[chef_tutorial]: https://learn.getchef.com/
[python_debugger]: https://docs.python.org/2/library/pdb.html
[dbintro]: https://www.coursera.org/course/db
[paas_tutorial]: https://devcenter.heroku.com/articles/getting-started-with-django
[pycharm]: https://www.jetbrains.com/pycharm/
[html5_book]: http://diveintohtml5.info/
[bootstrap]: http://getbootstrap.com/getting-started/
[cookies]: http://getfirebug.com/cookies
[css_guidelines]: http://cssguidelin.es/
[css_tutorial]: https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started
[less]: http://webdesign.tutsplus.com/articles/get-into-less-the-programmable-stylesheet-language--webdesign-5216
[devtools]: https://developer.chrome.com/devtools
[javascript_eloquent]: http://eloquentjavascript.net/
[javascript_goodparts]: http://shop.oreilly.com/product/9780596517748.do
[javascript_properly]: http://javascriptissexy.com/how-to-learn-javascript-properly/
[backbonejs]: http://javascriptissexy.com/learn-backbone-js-completely/
[ievms]: https://github.com/xdissent/ievms
[clean_code]: http://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882
[clean_coder]: http://www.amazon.com/The-Clean-Coder-Professional-Programmers/dp/0137081073
[continuous_delivery]: http://www.amazon.com/dp/0321601912?tag=contindelive-20
[tddbook]: http://www.amazon.com/Test-Driven-Development-By-Example/dp/0321146530
[tdd_udacity]: https://www.udacity.com/course/viewer#!/c-cs258/l-48449993/m-48739042
[cucumber_book]: http://www.amazon.com/Cucumber-Book-Behaviour-Driven-Development-Programmers/dp/1934356808
[webappsecurity]: https://google-gruyere.appspot.com/
[pep20]: http://legacy.python.org/dev/peps/pep-0020/
[top5cucumber]: http://blog.codeship.io/2013/05/21/Testing-Tuesday-6-Top-5-Cucumber-best-practices.html
[datastructspart1]: http://code.tutsplus.com/series/data-structures-succinctly-part-1--cms-551?view=grid
[virtualenv]: http://www.dabapps.com/blog/introduction-to-pip-and-virtualenv-python/
