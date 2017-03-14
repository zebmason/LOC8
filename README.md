# LOC8
A static analysis tool which suggests fixes for Lack of Cohesion problems

## Introduction

LOC8 is currently under development, this repository exists to track contributions to open-source projects made as a result of
using the tool to analyse their source code. Projects to be considered are those written in C++, C# and Visual Basic .NET.

Although LOC8 is a code review tool designed to address Lack of Cohesion problems it also attempts to find dead code.
The reasons for the existence of dead code include
* Missing conditional compilation guard. e.g. #if DEBUG
* Code under development. i.e. will be used due a later commit
* Lack of tidying after refactoring
* Broken code no longer calls the dead code

## Projects analysed

* [Mono.Cecil](Cecil.md)
* [Roslyn](Roslyn.md)

