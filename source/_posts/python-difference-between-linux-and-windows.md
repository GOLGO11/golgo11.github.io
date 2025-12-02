---
title: python difference between linux and windows
date: 2025-12-02 10:52:38
tags: [python, linux, windows]
---

## abstract
Python in linux is one of the core applications.
Python in winodws is only a extra application.

## python on linux
We should use the visual environment when developing and don't just develope with system core python.

### incorrect example
We went to use old version python for some reasons, so we download it.Then we want to switch system core python to the old version.We may find difficult because system base, system need the current python pack.So we remove current python.On ubuntu, this operation is availible, we tap "yes" and removing, You can see linux kernel also removing.It's over!

Whether you remove current python first or later, as long as you do it, it's over.

PS: On manjaro, you will be rejected when you remove current python

### correct use
We should use venv(visual environment).
We can select a python version downloaded, if we want to switch to other version, we can delete the generated folder and do it again.

## python on windows
The dangerous operation above do not exist on windows.windows do not depends on python, python is just an app on windows.
However, we usually develope more than one project, we also need visual env.

## conclusion
Use venv if you want to develop with python.

