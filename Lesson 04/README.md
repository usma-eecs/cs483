# Lesson 4 - File System Forensics II


## Table of Contents
- [Lesson Overview](#lesson-overview)
- [Learning Objectives](#learning-objectives)
- [Prerequisites](#prerequisites)
- [Lesson Topics](#lesson-topics)
- [Lesson Content](#lesson-content)
- [Additional Resources](#additional-resources)

## Lesson Overview

In this lesson, students will investigate Windows NTFS artifacts that can be used as evidence of program execution.

## Learning Objectives

- Identify evidence of program execution.
- Analyze various Windows artifacts for forensic value.

## Prerequisites

- Chapters 4, 8, and 11 of *File System Forensic Analysis*.

## Lesson Topics

1. Review Questions
   - What is a partition?
   - What is the MBR, and what valuable forensic information can be parsed from the MBR?
   - What is slack space?
   - What is the MFT?

2. Evidence of Execution Overview
   - Discuss snenarios where you may need to prove something executed on a machine.

3. Windows Prefetch
   - Cache of recent process information.
   - `C:\Windows\Prefetch`
   - `PECmd.exe`

4. Windows Registry Overview
   - Database hive that stores settings for the Windows OS and applications
   - Registry Explorer

5. ShimCache
   - Microsoft Application Compatibility Cache
   - `SYSTEM\ControlSet001\Control\SessionManager\AppCompatCache`
   - `AppCompatCacheParser`

6. Amcache
   - `Amcache.hve` tracks installed applications and loaded drivers
   - `SYSTEM\ControlSet001\Control\SessionManager\AppCompatCache`


## Lesson Content

You can find the lesson content in the [slides](https://github.com/usma-eecs/cs483/blob/main/Lesson%2004/Lesson%204%20-%20File%20System%20Forensics%20II.pptx) for this lesson.

## For Next Lesson

Work on File System Forensics Exercise.


## Additional Resources

- [Eric Zimmerman's Tools](https://ericzimmerman.github.io/#!index.md)
- [Amcache and ShimCache Forensic Analysis](https://andreafortuna.org/2017/10/16/amcache-and-shimcache-in-forensic-analysis/)

Students are encouraged to explore these resources for further learning.
