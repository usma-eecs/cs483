# Lesson 7 - Windows Internals II


## Table of Contents
- [Lesson Overview](#lesson-overview)
- [Learning Objectives](#learning-objectives)
- [Prerequisites](#prerequisites)
- [Lesson Topics](#lesson-topics)
- [Lesson Content](#lesson-content)
- [Additional Resources](#additional-resources)

## Lesson Overview

In this lesson, students will write basic programs using the Win32 API to learn more about Windows internals.

## Learning Objectives

- Research Win32 API Documentation
- Design, compile, execute, and troubleshoot simple Windows programs
- Explore Windows processes using Process Hacker

## Prerequisites

- Review previous lesson's content

## Lesson Topics

1. Using Visual Studios
   - Simple Hello World Program
   - `MessageBoxW`

2. Traversing Processes
   - Processes are managed as a doubly-linked list.
   - Use `CreateToolhelp32Snapshot` and `Process32First` and `Process32Next` to walk the list.

3. Enumerte System Information
   - `USER_SHARED_DATA` for OS version info
   - `GetNativeSystemInfo`
   - `GetWindowsDirectory`

4. Process Hacker
   - Use Process Hacker to explore your newly created processes.
   - Compare 32-bit and 64-bit processes.

## Lesson Content

You can find the lesson content in the [slides](https://github.com/usma-eecs/cs483/blob/main/Lesson%2007/Lesson%207%20-%20Windows%20Internals%20II.pptx) for this lesson.

## For Next Lesson

For the next lesson, practice writing some more Windows programs!


## Additional Resources

- [Windows Systems Programming](https://github.com/zodiacon/Win10SysProgBookSamples)

Students are encouraged to explore these resources for further learning.
