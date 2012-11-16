[Gaboogle! Bootstrap](https://github.com/gaboink/gaboogle-twitter-bootstrap)
=================

Gaboogle! Bootstrap is an extended clone of the sleek, intuitive, and powerful Twitter Boostrap front-end framework created to allow faster and easier web development.  Gaboogle! Bootstrap is created and maintained by [George Freeney-Jones](http://gaboink.com).



Extended Features
-----------

Videojs HTML5 Video Player Plugin - http://videojs.com/

To get started, clone https://github.com/gaboink/gaboogle-twitter-bootstrap!



Quick start
-----------

Clone the repo, `git clone git://github.com/gaboink/gaboogle-twitter-bootstrap.git`, [download the latest release](https://github.com/gaboink/gaboogle-twitter-bootstrap/zipball/master)



Developers
----------

We have included a makefile with convenience methods for working with the Bootstrap library.

+ **dependencies**
Our makefile depends on you having recess, connect, uglify.js, and jshint installed. To install, just run the following command in npm:

```
$ npm install recess connect uglify-js jshint -g
```

+ **build** - `make`
Runs the recess compiler to rebuild the `/less` files and compiles the docs pages. Requires recess and uglify-js. <a href="http://twitter.github.com/bootstrap/extend.html#compiling">Read more in our docs &raquo;</a>

+ **test** - `make test`
Runs jshint and qunit tests headlessly in [phantomjs](http://code.google.com/p/phantomjs/) (used for ci). Depends on having phantomjs installed.

+ **watch** - `make watch`
This is a convenience method for watching just Less files and automatically building them whenever you save. Requires the Watchr gem.



Contributing
------------

Please submit all pull requests against *-wip branches. If your unit test contains javascript patches or features, you must include relevant unit tests. Thanks!



Authors
-------

**George Freeney-Jones**

+ http://gaboink.com
+ http://github.com/gaboink



Copyright and license
---------------------

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
