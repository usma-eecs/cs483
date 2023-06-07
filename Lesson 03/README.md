# Lesson 3 - File System Forensics I


## Table of Contents
- [Lesson Overview](#lesson-overview)
- [Learning Objectives](#learning-objectives)
- [Prerequisites](#prerequisites)
- [Lesson Topics](#lesson-topics)
- [Lesson Content](#lesson-content)
- [Additional Resources](#additional-resources)

## Lesson Overview

In this lesson, students will learn about file system architectures, disk architecture, and file storage.

## Learning Objectives

- Discuss the storage hierachy at various layers of abstraction.
- Define common file system terms such as sectors, partitions, volumes, blocks, clusters, file system, and file attributes.

## Prerequisites

- read Chapter's 1-3 of *File System Forensic Analysis*.

## Lesson Topics

1. Storage Hierarchy Overview
   - File storage can be discussed at various levels of abstraction. This lesson will work from the bottom (physical) to the top (application layer).
   
2. Disk Architecture
   - Sectors, tracks, cylinders
   - Solid state drives (SSD)

3. Partitions and File Systems
   - Partitions, volumes
   - partition types, partition tables
   - Master Boot Record (MBR) and boot process (Linux)
   - GUID Partition Table
   - File systems defined and file system data categories
  
4. Space Management
   - Data units
   - Allocation and space management
   - Cluster sizes
   - Free space
   - Logical file addresses
   - Slack space
   - NTFS Volume Boot Records (VBR) and Master File Table (MFT)
 
 5. File Layer (Data)
   - File system structure
   - FAT and FAT32
   - NTFS
   - extX4
   - inode

6. Application Layer
   - Slack space
   - unallocated space
   - File attributes
   - `file` command


## Lesson Content

You can find the lesson content in the [slides](https://github.com/usma-eecs/cs483/blob/main/Lesson%2003/Lesson%203%20-%20File%20System%20Forensics%20I.pptx) for this lesson.

## For Next Lesson

Read Chapters 4, 8, and 11 of *File System Forensic Analysis*.


## Additional Resources

- [Master Boot Record (MBR)](http://www.invoke-ir.com/search/label/Master%20Boot%20Record)
- [GUID Partition Table](http://www.invoke-ir.com/search/label/Guid%20Partition%20Table)
- [Windows File Systems](https://learn.microsoft.com/en-us/windows/win32/FileIO/file-systems)

Students are encouraged to explore these resources for further learning.
