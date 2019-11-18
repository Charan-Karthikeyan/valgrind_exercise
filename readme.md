# Valgrind Exercise

[![Build Status](https://travis-ci.org/Charan-Karthikeyan/valgrind_exercise.svg?branch=master)](https://travis-ci.org/Charan-Karthikeyan/valgrind_exercise)
[![Coverage Status](https://coveralls.io/repos/github/Charan-Karthikeyan/valgrind_exercise/badge.svg?branch=master)](https://coveralls.io/github/Charan-Karthikeyan/valgrind_exercise?branch=master)
---

## Overview
Overview of valgrind
Simple starter C++ project with:

- cmake
- googletest

## Standard install via command-line
```

mkdir build
cd build
cmake ..
make
Run tests: ./test/cpp-test
Run program: ./app/shell-app
```

## Building for code coverage (for assignments beginning in Week 4)
```
sudo apt-get install lcov
cmake -D COVERAGE=ON -D CMAKE_BUILD_TYPE=Debug ../
make
make code_coverage
```
This generates a index.html page in the build/coverage sub-directory that can be viewed locally in a web browser.


