Steps to build this project with biicode:

~~~
$ git clone
$ cd to-project-folder
$ bii init -L
$ bii test
~~~

Note that all CMakelists have been removed from the repo, they are actually not required. They could be left in place, it is just for demostration purposes.


Original instructions:

A sample project illustrating how to perform unit testing with GoogleTest and CMake

##Building

~~~
mkdir build
cd build
cmake ..
make
~~~

##Running

~~~
cd build && make test
~~~

or

~~~
build/test/testfoo/testfoo
~~~

Refer to [this blog post](http://kaizou.org/2014/11/gtest-cmake/) for a detailed explaination of how it works.
