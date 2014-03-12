blog
====

A running blog of Dinkum Software's open source development activity not elsewhere documented.

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

2014-03-12 tc@DinkumSoftware.com 

Been struggling for some time with transitioning from subversion with private
servers to open source at git hub and publishing 10 years of accumulated useful
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


