# Travis-CI-Python-versions
What versions of Python are available on Travis CI default installs

| OS, Dist, Language    | pyenv | Py 2.7 | Py 3.5 | Py 3.6 | Py 3.7 | notes... |
| --------------------- | ----- | ------ | ------ | ------ | ------ | -------- |
| linux, trusty, python | 1.1.5 | __2.7.14__ | __3.5.6__ | __3.6.3__ | N/A | python: x.y |
| linux, xenial, cpp    | 1.1.5 | 2.7.14 | 3.5.6 | 3.6.7 | 3.7.1 | pyenv install x.y.z ; pyenv global x,y,z |
| osx                   | 1.2.4 | __2.7.15__ | 3.5.4 | 3.6.5 | 3.7.3 | pyenv install x.y.z ; pyenv global x,y,z |
| windows               |  N/A  | 2.7.16 | 3.5.4 | 3.6.8 | 3.7.3 | choco install python --version x.y.z |
