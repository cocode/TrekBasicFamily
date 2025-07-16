# TrekBasic

TrekBasic is a family of compilers, interpreters and tools for the BASIC programming langugage.

All compiler and interpreter versions are intended to by byte-by-byte compatible. They are not there 
yet, but they are close. TrekBot and BasicTestSuite are part of the
plan to ensure full compatibility.

## Why 'Trek'?
The initial goal was to be able to play the old [Super Star Trek game](https://en.wikipedia.org/wiki/Star_Trek_(1971_video_game)),
which was written in BASIC. That goal has been achieved.

## TrekBasic Family

TrekBasic is part of the TrekBasic family of BASIC programming tools.

| Tool | Description | Language | Interpreter | Compiler | Graal |
|------|-------------|----------|-------------|----------|-------|
|[TrekBasic](https://github.com/cocode/TrekBASIC) | Basic compiler and interpreter | Python | Yes | Yes | - |
|[TrekBasicJ](https://github.com/cocode/TrekBasicJ)|Basic compiler and interpreter|Java|Yes|Yes|pending|
|[BasicRS](https://github.com/cocode/BasicRS)|Basic compiler written|Rust|Yes|pending|-|
|[BasicTestSuite](https://github.com/cocode/BasicTestSuite)|A test suite for Basic|BASIC||-|-|-||
[TrekBot](https://github.com/cocode/TrekBot)|A tool to exercise the superstartrek program|Rust|


## Tools

### TrekBot
TrekBot is a bot that plays Super Star Trek. It's use for testing, and code coverage. 

There is also a Python version of TrekBot, but it cheats by accessing internal data structures of the Python version of TrekBasic, 
and is therefor only usable with TrekBasic in Python. 

The Rust version of TrekBot uses the same UI as humans, and so can be run against any implementation that uses stdin/stdout.

### Basic Test Suite
THe Basic Test Suite is a series of programs, written in BASIC, to test an implementation. With a proper test runner, you can run the programs, as well as check return code and excpetions.

Each implementation has a test runner. (TrekBasic, TrekBasicJ, BasicRS)



