# TrekBasic

TrekBasic is a family of compilers, interpreters and tools for the BASIC programming language.

All compiler and interpreter versions are intended to be byte-by-byte compatible. They're not there 
yet — but they are close. TrekBot and BasicTestSuite are part of the
plan to ensure full compatibility.

## TrekBasic Family

TrekBasic is part of the TrekBasic family of BASIC programming tools.

| LOGO | Tool | Description | Language | Interpreter | Compiler |
|-|------|-------------|----------|-------------|-------------|
|<img src="https://raw.githubusercontent.com/cocode/TrekBASIC/refs/heads/master/images/TrekBasicLogo.png" alt="Logo" width="50" height="25">|[TrekBasic](https://github.com/cocode/TrekBASIC) | Basic compiler and interpreter | Python | Yes | Yes |
|<img src="https://raw.githubusercontent.com/cocode/TrekBasicJ/main/images/logo7.png" alt="Logo" width="50" height="25">|[TrekBasicJ](https://github.com/cocode/TrekBasicJ)|Basic compiler and interpreter|Java|Yes|Yes|
|<img src="https://raw.githubusercontent.com/cocode/BasicRS/master/images/logo2.png" alt="Logo" width="50" height="25">|[BasicRS](https://github.com/cocode/BasicRS)|Basic interpreter|Rust|Yes|pending|
|<img src="https://github.com/cocode/BasicTestSuite/blob/main/images/BasicTestSuiteLogo3.png" alt="Logo" width="50" height="25">|[BasicTestSuite](https://github.com/cocode/BasicTestSuite)|A test suite for Basic|BASIC|-|-|
|<img src="https://raw.githubusercontent.com/cocode/TrekBot/master/images/LogoTrans.png" alt="Logo" width="50" height="25">|[TrekBot](https://github.com/cocode/TrekBot)|A tool to exercise the superstartrek program|Rust|-|-|


## Tools

### TrekBot
TrekBot is a bot that plays Super Star Trek. It's used for automated testing and code coverage. 

* The **Rust version** behaves like a human player by using stdin/stdout, making it compatible with any text-based implementation.
* The **Python Version** of TrekBot works by accessing internal data structures of the Python version of TrekBasic, 
and is therefore only usable with TrekBasic in Python. 

### Basic Test Suite
The **Basic Test Suite** is a collection of BASIC programs used to test interpreter and compiler behavior.  
With a proper test runner, it can execute programs and verify return codes and exceptions.

Each implementation (TrekBasic, TrekBasicJ, BasicRS) includes its own runner.

## Why 'Trek'?
The initial goal was to be able to play the old [Super Star Trek game](https://en.wikipedia.org/wiki/Star_Trek_(1971_video_game)),
which was written in BASIC. That goal has been achieved.

