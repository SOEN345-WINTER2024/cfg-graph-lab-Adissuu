# Soot Tutorial
[![Build Status](https://travis-ci.com/noidsirius/SootTutorial.svg?branch=master)](https://travis-ci.com/noidsirius/SootTutorial)

This repository contains (will contain) several simple examples of static program analysis in Java using [Soot](https://github.com/Sable/soot).

## Who this tutorial is for?
Anybody who knows Java programming and wants to do some static analysis in practice but does not know anything about Soot and static analysis in theory.

If you have some knowledge about static program analysis I suggest you learn Soot from [here](https://github.com/Sable/soot/wiki/Tutorials).

### [Why another tutorial for Soot?](https://github.com/noidsirius/SootTutorial/blob/master/docs/Other/Motivation.md)

## Setup
[Setup](https://github.com/noidsirius/SootTutorial/blob/master/docs/Setup/)
  
## Chapters
### 1: Get your hands dirty

In this chapter, you will visit a very simple code example to be familiar with Soot essential data structures and **Jimple**, Soot's principle intermediate representation.

|Title |Tutorial | Soot Code        | Example Input  |
| :---: |:-------------: |:-------------:| :-----:|
|Hello Soot |[Doc](https://github.com/noidsirius/SootTutorial/blob/master/docs/1/)      | [HelloSoot.java](https://github.com/noidsirius/SootTutorial/tree/master/src/main/java/dev/navids/soottutorial/hellosoot/HelloSoot.java) | [FizzBuzz.java](https://github.com/noidsirius/SootTutorial/tree/master/demo/HelloSoot/FizzBuzz.java) |

<img src="https://github.com/noidsirius/SootTutorial/blob/master/docs/1/images/cfg.png" alt="Control Flow Graph" width="400"/>

### 2: Some *Real* Static Analysis (:construction: WIP)
### 3: Manipulate the code (:construction: WIP)
### 4: Call Graphs (:construction: WIP)
### 5: Interprocedural analysis (:construction: WIP)
### 6: Android (:construction: WIP)

|Title |Tutorial | Soot Code        | Example Input  |
| :---: |:-------------: |:-------------:| :-----:|
|Trace an APK| | [AndroidTracer.java](https://github.com/noidsirius/SootTutorial/tree/master/src/main/java/dev/navids/soottutorial/android/AndroidTracer.java) | |



  
## Run the analyzer
### HelloSoot

* `./gradlew run` will analyze `printFizzBuzz` method of `FizzBuzz` class located in `demo/HelloSoot/FizzBuzz.class`.
  * In order to see a visualization of `printFizzBuzz` control-flog graph execute `./gradlew run --args='draw'`
