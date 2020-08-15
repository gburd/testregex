cmake_minimum_required(VERSION 3.17)
project(att_regex_tester)

set(CMAKE_CXX_STANDARD 14)

add_executable(att_regex_tester
        man/man1/testregex.html
        basic.dat
        categorize.dat
        forcedassoc.dat
        leftassoc.dat
        nullsubexpr.dat
        re-assoc.html
        re-categorize.html
        re-interpretation.html
        re-nullsubexpr.html
        re-repetition.html
        re2-exhaustive.txt.bz2
        re2-search.txt
        README.md
        repetition.dat
        rightassoc.dat
        testregex.c
        testregex.html)
