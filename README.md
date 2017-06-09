# toolbox <img src="https://image.flaticon.com/icons/png/512/31/31353.png" width="70"/>

Sometimes can't remember what's all in my toolbox ¯\_(ツ)_/¯ These are CLI tools - not libraries or services. (although some tools are implemented as libraries I guess...)
Making this repo because my stars get cluttered with tools, services, libraries, compilers, interpreters, code-I-just-wanna-read, projects-that-I-wanna-contribute-to.
This is the lazy way of cleaning out the closet.

The idea behind this is before starting any project, I can come here and decide at the beginning of the projects which tools I'd like to incorporate to improve developer productivity from the get-go.

Contents:
 - [Networking](#networking)
 - [Load Testing](#load-testing)
 - [C/C++ Programming](#cc-programming)
 - [Go Programming](#go-programming)
 - [Python Programming](#python-programming)
 - [Lua Programming](#lua-programming)
 - [Nginx Development](#nginx-development)
 - [PostgreSQL](#postgresql)
 - [General Web Analysis](#general-web-analysis)
 - [Reverse Engineering](#reverse-engineering)
 - [General SysAdminship](#general-sysadminship)

### Networking

[dig](https://linux.die.net/man/1/dig) - DNS lookup utility built into Unix

[dt](https://github.com/42wim/dt) - DNS information about a domain

[netstat](https://linux.die.net/man/8/netstat) - Unix utility for displaying network connections

nslookup - query nameservers interactively, also built into Unix

[dnsdiff](https://github.com/joshenders/dnsdiff) - compare responses from 2 different nameservers

[dnsviz](https://github.com/dnsviz/dnsviz) - visualize DNS information ([companion site](http://dnsviz.net/))

[httpie](https://github.com/jakubroztocil/httpie) - fancy cURL utility

[passivedns](https://github.com/gamelinux/passivedns)

[httpbin](http://httpbin.org/) - various HTTP scenarios you can use to test your server

[mockbin](http://mockbin.org/) - similar to Httpbin

[requestb.in](https://requestb.in/) - similar to above, mock HTTP requests

[putsreq](http://putsreq.com/) - also similar to above, mock HTTP requests

[httpstat](http://httpstat.us/) - returns a any specified HTTP status code

### Load Testing

[hey](https://github.com/rakyll/hey)

[siege](https://github.com/JoeDog/siege)

[wrk](https://github.com/wg/wrk)

[vegeta](https://github.com/tsenart/vegeta)

### Servers

[uwsgi](https://uwsgi-docs.readthedocs.io/en/latest/) + [uwsgitop](https://github.com/xrmx/uwsgitop) - WSGI server (sits in between application and proxy) + Monitoring/Statistics. APIs for Python, Perl, Ruby, and Lua.

### C/C++ Programming

[infer](https://github.com/facebook/infer) - static analyzer for Java, C, C++, and Objective-C (geared towards mobile development?)

[Valgrind](http://valgrind.org/) - memory profiler and other goodies to keep your 1's and 0's in line.

[include-what-you-use](https://github.com/include-what-you-use/include-what-you-use) - Analyze headers to reduce unnecessary imports

[ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) - automated formatting

[CppCheck](http://cppcheck.sourceforge.net/) - static analysis

### Go Programming

[golint](https://github.com/golang/lint)

[gofmt](https://golang.org/cmd/gofmt/) - automated formatting, built into Go distribution

### Python Programming

[pyheat](https://github.com/csurfer/pyheat) - profiler

[profiling](https://github.com/what-studio/profiling) - profiler

[mypy](https://github.com/python/mypy) - static type-checker

[nose](https://github.com/nose-devs/nose) - test-runner

[fabric](https://github.com/fabric/fabric) - remote task execution/automation

[tox](https://github.com/tox-dev/tox) - virtualenv management and test command line tool

[pylint](https://github.com/PyCQA/pylint) - Python source analyzer

### Lua Programming

[luacheck](https://github.com/mpeterv/luacheck)

### Nginx Development

[gixy](https://github.com/yandex/gixy) - Nginx config static analyzer

### PostgreSQL

[pgweb](http://sosedoff.github.io/pgweb/) - web interface to PostgreSQL

[DBShield](https://github.com/nim4/DBShield) - application firewall to sit in front of your database, protect against suspicious queries and whatnot

### General Web Analysis

[http-observatory](https://github.com/mozilla/http-observatory)

[tmi](https://github.com/addyosmani/tmi) - evaluate "image weight" of your website

[psi](https://github.com/addyosmani/psi) - Pagespeed insights reporting

[performance-bookmarklet](https://github.com/micmro/performance-bookmarklet) - Browser extension to provide in-depth performance analysis of a webpage.

[pshtt](https://github.com/dhs-ncats/pshtt) - HTTPS analyzer

Chrome Developer Tools :)

### Reverse Engineering

gdb - GNU debugger, built into Unix, with its own [scripting language](http://www.adacore.com/adaanswers/gems/gem-119-gdb-scripting-part-1/). Also very useful for general Unix debugging

[gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard)

[gdbgui](https://github.com/cs01/gdbgui) - a GUI for GDB

[radare2](https://github.com/radare/radare2) - reverse engineering / decompiling tool


### General SysAdminship

[ctop](https://github.com/bcicen/ctop) - `top` for containers

gdb - see RE section

[goss](https://github.com/aelsabbahy/goss) - Server configuration validation/testing



- - - -
Toolbox icon made by <a href="http://www.freepik.com" title="Freepik">Freepik</a> from <a href="http://www.flaticon.com" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
