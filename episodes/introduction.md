---
title: "Introduction to Build Systems"
teaching: 10
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions

- What is a build-system?
- Why would I use a build system?
- Can I and should I generate my build system?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain the basic build process of compiled languages.
- Explain reasons for automating the build of an application.
- Demonstrate challenges from manually configuring and building an application/

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This paragraph is still a placeholder.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

It is important to help course participants understand the motivation of
automating as much of an application's or library's build process as possible.
Moreover, an additional discussion about the motivations for build-system
generators, such as CMake, helps in generating a common understanding of
the challenges.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge

## Challenge 1: Can you name build systems use for differnet software?

You have likely come across several build systems when using software. Can you
name some of them?

:::::::::::::::::::::::: solution

## Output

```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


## Challenge 2: Can you name the difference between a build system and a build-system generator?

:::::::::::::::::::::::: solution

A build system contains all the rules and task description for building a
specifc part of a software.

A build-system generator creates the files for a specific build system to
build a specific part of a software.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: keypoints

- Successfully building an application can become can be cumbersome quickly as
  application complexity rises.
- Use of a build system can automate many of the tasks comprised
- Generating build system files can further automate adaptation to different
  computers and/or versions of dependencies.

::::::::::::::::::::::::::::::::::::::::::::::::


