dinkum-blog
====

A running blog of Dinkum Software's open source development activity
not elsewhere documented.

Copyright 2014 Dinkum Software

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

This is 80 characters.
         1         2         3         4         5         6         7         8
123456789.123456789.123456789.123456789.123456789.123456789.123456789.123456789.

2014-03-12 tc@DinkumSoftware.com 

Been struggling for some time with transitioning from subversion with private
servers to open source at git hub and publishing 20+ years of accumulated useful
utilities.

So I'm in that process and I created a public git repo: dinkumsoftware/blog to
hold my working notes until I get my infrastructure stable.  I think I made
an initial mistake naming it blog, thinking that git user dinkumsoftware would
distinguish it.  But it gets "cloned" to just blog.

Now, I made my first mistake, didn't take long.
So all my repos should start with dinkum-.  Kill this blog and recreate it
as dinkumsoftware/dinkum-blog.

Turns out I can rename it in github:

https://help.github.com/articles/renaming-a-repository
Under repo settings

I originally wanted to put all my work under GNU license, but that means
that others can't incorporate it with proprietary software.  While I'm
a long time user of open source stuff, I'm hoping future real-time stuff
gets used by real vendors and GNU would limit it's distribution.

GNU recommended apache 2.0 for non-copyleft, so that's what I'll use for
software:
http://directory.fsf.org/wiki/License:Apache2.0

GNU recommends GFDL for big complicated documentation.
I'll probably use that web pages and manuals:

For really small files, GNU recommends:
https://www.gnu.org/prep/maintain/html_node/License-Notices-for-Other-Files.html

GIT only "knows about Apache 2.0, So for now I'll put everything under that.

I'm writing in Markdown, so I ought to know a little about it.
http://guides.github.com/overviews/mastering-markdown/

I made some initial wiki pages using on-line editor.
For now, just keeping the blog in the readme.md.  github has capability to
generate html (under dinkumsoftware.org if I want).  I'll need to explore that
sometime.

Enough for tonite.

2014-03-13 tc@DinkumSoftware.com 

The general thrust here is to do open source python development.  I need
reasonable project structure for python.  I'm mucked around a bit over the
last year without coming up with my own solution.  Found a great web site
that generally covers it all:
http://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/

I'm in agreement with most of the things he says and he lead me to
cookiecutter which seems like a great solution for generating project
templates and use on line resources for testing, packaging, and
distributing python code.  I want to eventually end up with
dinkum-project a python "package" with some executables that let me
generate a new project with a one-liner, allow refactoring between
projects etc.  But I need small steps.

So near term goal:

- repo:dinkum-sandbox
  - executables:
    - *dinkum_sandbox_hello.py*      prints hello
    - *dinkum_sandbox_goodbye.py*    prints goodbye

As I am writing markdown for my first time, I git pushed and had a couple of
problems.
TODO

   - [x] the mention of jeffknupp wasn't highlighted.
         Turns out @mentions only work in descriptions and comments of
         Issues and Pull requests.
   - [x] the formatting of my near term goals all ran together.

Struggling with MarkDown.  GitHub has some GitHub only MarkDown enhancements.
Some of them only show up in descriptions/comments in Issues/Pull requests.
i.e. not this file.  Some seems to work in all files (like this one).

Apparently regular markdown (like html, etc) treat a new-line as regular white
space.  GitHub treats a new-line differently.  Now my problem is that my brain
is hardwired to hit enter at the edge of a screen in emacs and github renders it
to that width.  For now, keep my emacs window at 80 columns and keep hitting
the enter key.

Where's the MarkDown documentation?
[GitHub Documentation]
        (https://help.github.com/categories/88/articles)

Where's the "official" markdown reference?   Well according to (wikipedia)
[http://en.wikipedia.org/wiki/Markdown] there isn't any standard.  Note
that there is an emacs plugin. TODO

-[ ] get emacs markdown plugin

GFM github flavored markdown seems popular.

Here is a [live online Markdown Here page]
     (http://markdown-here.com/livedemo.html)
It is yet another variant of markdown,
but it follows GFM conventions on new lines. @adam-p

[John Gruber, the original authors spec]
      (http://daringfireball.net/projects/markdown/syntax)

My todo marker has historically been todo inside of angle brackets, but it
disappears.  Since you can write in-line html, MarkDown gobbles up what
look like html tags.  So I need to change my TODO marker.

What does eclipse use by default?  Looks like TODO .. use that.
Follow the GFM task list convention for todo's even though it
doesn't seem to work in Markdown files in the project (like this one).  It
is still readable.

Fixed up the formatting for short term dinkum-sandbox list.

Make some dinkum markdown rules on wiki
- dinkumsoftware markdown rules
  - text in 80 column windows with hard returns
  - TODO is the todo marker
  - Use GFM task lists for todo lists







