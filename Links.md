## LaTeX

* [XeLaTeX mgr](https://github.com/wbzyl/xelatex-mgr) –
  praca magisterska w LaTeX-u
* prezentacje przygotowujemy korzystając z [Slides](http://slid.es/)
  lub to samo, ale wpisujemy slajdy samemu korzystając z [Reveal.js](http://lab.hakim.se/reveal-js/)
  Można użyć dowolnego narzędzia do tworzenia/generowania tzw. *browsable slides*, na przykład
  [PwrSlide](https://github.com/wvandaal/PwrSlide)
  ([demo](http://wcvd.me/PwrSlide/), [theming](https://github.com/wvandaal/PwrSlide/tree/master/theme));
  zob. też wtyczkę [Emmet](http://emmet.io/)


## Crash course web / browser performance

1. Ilya Grigorik:
  * [Bandwidth, latency, and radio performance](https://www.youtube.com/watch?v=7gtf47D_bu0)
  * [Optimizing networking performance (and HTTP 2.0)](https://www.youtube.com/watch?v=46exugLbGFI)
  * [Critical rendering path](https://www.youtube.com/watch?v=PkOBnYxqj3k)
  * [Making Web Fonts Fast(er)](http://velocityconf.com/velocity2014/public/schedule/detail/35201)
1. Ilya Grigorik, [High-Performance Browser Networking](http://chimera.labs.oreilly.com/books/1230000000545/index.html).
1. [Give your app a first-class tune-up](https://developer.att.com/application-resource-optimizer).


## HOWTOs

* Simon Peyton Jones,
  - [How to write a good research paper](http://research.microsoft.com/en-us/um/people/simonpj/papers/giving-a-talk/writing-a-paper-slides.pdf)
  - [How to write a good research proposal](http://research.microsoft.com/en-us/um/people/simonpj/papers/Proposal.html)
    (razem z A. Bundy)
  - [How to give a good research talk](http://research.microsoft.com/en-us/um/people/simonpj/papers/giving-a-talk/giving-a-talk-slides.pdf)
* Jennifer Raff.
  [How to read and understand a scientific paper: a guide for non-scientists](http://violentmetaphors.com/2013/08/25/how-to-read-and-understand-a-scientific-paper-2/)


## Git

* [Seth Robertson](http://sethrobertson.github.io/),
  - [Git Best Practices](http://sethrobertson.github.io/GitBestPractices/)
  - [On undoing, fixing, or removing commits or mistakes in git](http://sethrobertson.github.io/GitFixUm/fixup.html)
  - [Post-Production Editing using Git](http://sethrobertson.github.io/GitPostProduction/gpp.html)


> During the program life a programmer team possessing its theory
> remains in active control of the program, and in particular retains
> control over all modifications.<br>
> The death of a program happens when
> the programmer team possessing its theory is dissolved.<br>
> A dead program may continue to be used for execution in a computer and to produce
> useful results. The actual state of death becomes visible when demands
> for modifications of the program cannot be intelligently answered.<br>
> Revival of a program is the rebuilding of its theory by a new programmer team.<br>
> *Peter Naur*

## Technologie do wykorzytania w aplikacjach

1\. [Web Components](http://w3c.github.io/webcomponents/explainer/) –
[The Web’s Declarative, Composable Future](http://addyosmani.com/blog/the-webs-declarative-composable-future/)
by Addy Osmani.
- Peter Gasston.
  [A Detailed Introduction To Custom Elements](http://coding.smashingmagazine.com/2014/03/04/introduction-to-custom-elements/)
- [Templates](http://w3c.github.io/webcomponents/explainer/#template-section)
  *  [HTML’s New Template Tag](http://www.html5rocks.com/en/tutorials/webcomponents/template/)
- [Custom Elements](http://w3c.github.io/webcomponents/explainer/#custom-element-section)
  * Eric Bidelman. [Custom Elements](http://www.html5rocks.com/en/tutorials/webcomponents/customelements/)
  * *MDN*. [Custom Elements](https://developer.mozilla.org/en-US/Apps/Tools_and_frameworks/Custom_elements)
- [Shadow DOM](http://w3c.github.io/webcomponents/explainer/#shadow-dom-section)
  * Dominic Cooney. [Shadow DOM 101](http://www.html5rocks.com/en/tutorials/webcomponents/shadowdom/)
- Ilya Grigorik.
  [Web Components can do that?!](http://addyosmani.github.io/fitc-wccdt/)


2\. [Polymer](http://www.polymer-project.org/) – building blocks for the WEB:
* [Difference between Bower and NPM?](http://stackoverflow.com/questions/18641899/difference-between-bower-and-npm)
* [prism](http://prismjs.com/)
* [prism-js](https://github.com/addyosmani/prism-js)
* [emcee](https://github.com/ahuth/emcee) –
  package web components in Rails applications using the asset pipeline
* [Polymer Sandbox](http://www.polymer-project.org/tools/sandbox/)

3\. LXC:
* [LXC 1.0: Blog post series [0/10]](https://www.stgraber.org/2013/12/20/lxc-1-0-blog-post-series/)

4\. Docker:
* [What does Docker add to just plain LXC?](http://stackoverflow.com/questions/17989306/what-does-docker-add-to-just-plain-lxc)
* [How is Docker.io different from a normal virtual machine?](http://stackoverflow.com/questions/16047306/how-is-docker-io-different-from-a-normal-virtual-machine)
* [Docker in education: From VMs to Containers](http://blog.docker.io/2014/04/docker-in-education-interview/)
* Using Docker for MOOCs:
  - [part 1](http://mjbright.blogspot.fr/2014/04/using-docker-for-moocs-part-1.html)
* Marconi Moreto.
  [Introduction to Docker](https://speakerdeck.com/marconi/introduction-to-docker)
* Kyle Mathews.
  [Hosting static sites with Docker and Nginx](http://bricolage.io/hosting-static-sites-with-docker-and-nginx/)

5\. Tools for automating development workflow:
- [Yeoman](https://github.com/yeoman/yeoman)
- Addy Osmani. [Building Web Apps With Yeoman And Polymer](http://www.html5rocks.com/en/tutorials/webcomponents/yeoman/)
- Shekhar Gulati. [Yeoman Ember--The Missing Tutorial](https://www.openshift.com/blogs/day-24-yeoman-ember-the-missing-tutorial)

6\. Mutation observers, Object observers (JavaScript, Angular, Ember.js):
- [Object observe](http://weblog.bocoup.com/javascript-object-observe/);
  [Fact](https://github.com/rwaldron/fact) –
  observable, event emitting data objects w/ Object.observe and EventEmitter2 in 2.4k
- [Mutation summary](https://code.google.com/p/mutation-summary/) –
  a JavaScript library that makes observing changes to the DOM fast, easy and safe

7\. [ES.next showcase](https://github.com/sindresorhus/esnext-showcase).
- [Promises](http://www.html5rocks.com/en/tutorials/es6/promises/)
- Matt Greer.
  [JavaScript Promises … In Wicked Detail](http://mattgreer.org/articles/promises-in-wicked-detail/)

8\. Ruby:
- [Rails assets](https://rails-assets.org/)

----

1. [Farewell Letter Generator](http://tinysubversions.com/stuff/farewell/) by Darius Kazemi.
