# CSE207 - Section 3 - ANTU - GROUP 4 - Member 1

**Project Number from List:** 04  
**Project Title:** E-Commerce Order Processing System

---

## Overview

>E-Commerce is becoming an integral part of daily life, with platforms like Amazon and Alibaba leading the market. This project implements a bare-bones **E-Commerce Order Processing System** in C, designed to manage customers, products, and orders efficiently using various data structures.

---

## Features

1. **Customer Management**: Add, remove, and display customers.  
2. **Product Management**: Add, remove, and display products stored in a Binary Search Tree (BST).  
3. **Order Management**: Place and process orders using a Queue.  
4. **Undo Functionality**: Track recent order changes using a Stack for undo operations.

---

## Data Structures Used

| Entity    | Data Structure           | Purpose                                                   |
|-----------|-------------------------|-----------------------------------------------------------|
| Customers | Linked List             | Stores and manages customer information such as name and ID. |
| Products  | Binary Search Tree (BST)| Stores and searches products efficiently.                |
| Orders    | Queue                   | Manages order processing in FIFO order.                  |
| Undo      | Stack                   | Tracks recent order changes for undo operations.         |

---

## Dependencies

- `stdio.h`  
- `stdlib.h`  
- `string.h`  

---

## Installation & Running the Program

1. Install **CodeBlocks** with the prebuilt **Mingw compiler** -'codeblocks-25.03mingw-setup.exe' from [CodeBlocks](https://www.codeblocks.org/) or SourceForge.  
2. Download the `.c` file: `ECommerce2024-1-60-278.c`.  
3. Open the file in CodeBlocks.  
4. Click the **Build and Run** button (gear and play icon).  
5. A command prompt interface will open, and the program will prompt you for input.
