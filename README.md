Web development starter kit
===========================

This is a collection of resources that has helped web developers at Prezi to become great and happy developers. It's a curated list of books, articles and tutorials. It's based on the current technology stack that we use at Prezi but it's useful for every full stack developer.

## Introductory topics

- learn data structures
    - **book: [Data Structures and Algorithms][data_struct]**
    - article: [Data Structures Succinctly: Part 1][datastructspart1]
- be familiar with basic Unix tools
    - **book: [The Unix Programming Environment][unix_book]**
    - **tutorial: [Unix tutorial][unix_tutorial]
- learn version controlling
    - **tutorial: [Git tutorial][git_school] (time investment: 15 min)**
- learn regular expressions
    - **tutorial: [RegExp tutorial][regex_tutorial]**
- understand HTTP and browsers
    - **article: [How Browsers Work: Behind the scenes of modern web browsers][browserswork]**
    - **article: [HTTP: The Protocol Every Web Developer Must Know][http_tutorial]**

## Backend technologies
- be familiar with the Python coding style
    - **article: [PEP 8][pep8] (time investment: 2 hours)**
    - **article: [PEP 20 aka The Zen of Python][pep20] (time investment: 2 min)**
- be able to bootstrap a Django app from scratch
    - **tutorial: [official Django tutorial][django_tutorial]**
    - **book: [Two Scoops of Django: Best Practices For Django 1.6][scoops_of_django]
- i18n
    - **article: [Internationalization and localization][i18n]
- have Chef installed & try basic tasks
    - **tutorial: [Chef course][chef_tutorial]
- learn to use the Python debugger
    - **article: [PDB][python_debugger]**
- learn databases
    - **tutorial: [SQL tutorial][sql_tutorial]**
- be able to setup a website or service on heroku or amazon (PAAS)
    - **tutorial: [Getting Started with Django on Heroku][paas_tutorial]**
- have a good python IDE installed
    - **recommendation: prezi engineers recommend using [PyCharm][pycharm]

## Frontend technologies
- understand how HTML and CSS work
    - **book: [Dive into HTML5][html5_book]**
    - **tutorial: [CSS tutorial][css_tutorial]**
    - **tutorial: [CSS Bootstrap tutorial][bootstrap]**
    - **article: [CSS guidelines][css_guidelines]
    - **tutorial: [LESS framework][less]
    - **article: [website cookies][cookies]**
- understand the basics of JavaScript
    - **book: [Eloquent JavaScript: A Modern Introduction to Programming][javascript_eloquent] (if you are new to programming)**
    - **book: [JavasCript: Good Parts][javascript_goodparts]:**
    - **tutorial: [learn JavaScript properly][javascript_properly] (time investment: 8 week)
- browser dev tools
    - **article: [devtools][devtools]
- learn a JavaScript framework
    - **article: [learn backbone.js completely][backbonejs]
- be familiar with a virtualization tool for hosting services and for cross-browser development
    - **recommendation: prezi engineers recommend [ievms][]

## Advanced topics
- write clean code -- great engineers write clean code to help us create maintainable systems
    - **book: [Clean code][clean_code]**
    - **book: [Clean Coder][clean_coder]
- be familiar with basic development processes
    - **book: [Continuous Delivery][continuous_delivery]**
- learn about the importance of automated unit tests and how TDD can help you write better code
    - **book: [TDD by example][tddbook]**
    - **video: [lecture #1 of Udacity Software Testing][tdd_udacity] about unit testing with coding exercises
- have an understanding of acceptance testing
    - **book: [The Cucumber Book][cucumber_book]
    - **video: [Top 5 Cucumber best practices][top5cucumber]
- learn about web application security principles
    - **article: [ Web Application Exploits and Defenses][webappsecurity]

[data_struct]: http://www.amazon.com/Data-Structures-Algorithms-Alfred-Aho/dp/0201000237
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
[sql_tutorial]: http://www.sqlcourse.com/
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
