---
sticker: lucide//airplay
---
# [[9618-2024-2025-syllabus.pdf|Syllabus]]

# [[Hodder AS and A Levels Computer Science.pdf|Text book]]

# Contents
- ### [[1 Information representation]]
	- [[1.1 Data Representation]]
	- [[1.2 Multimedia – Graphics, Sound]]
	- [[1.3 Compression]]
- ### [[2 Communication]]
	- [[2.1 Networks including the internet]]
- ### [[3 Hardware]]
	- [[3.1 Computers and their components]]
	- [[3.2 Logic Gates and Logic Circuits]]
- ### [[4 Processor Fundamentals]]
	- [[4.1 Central Processing Unit (CPU) Architecture]]
	- [[4.2 Assembly Language]]
	- [[4.3 Bit manipulation]]
- ### [[5 System Software]]
	- [[5.1 Operating Systems]]
	- [[5.2 Language Translators]]
- ### [[6 Security, privacy and data integrity]]
	- [[6.1 Data Security]]
	- [[6.2 Data Integrity]]
- ### [[7 Ethics and Ownership]]
	- [[7.1 Ethics and Ownership]]
- ### [[8 Databases]]
	- [[8.1 Database Concepts]]
	- [[8.2 Database Management Systems (DBMS)]]
	- [[8.3 Data Definition Language (DDL) and Data Manipulation Language (DML)]]
- ### [[9 Algorithm Design and Problem-solving]]
	- [[9.1 Computational Thinking Skills]]
	- [[9.2 Algorithms]]
- ### [[10 Data Types and Structures]]
	- [[10.1 Data Types and Records]]
	- [[10.2 Arrays]]
	- [[10.3 Files]]
	- [[10.4 Introduction to Abstract Data Types (ADT)]]
- ### [[11 Programming]]
	- [[11.1 Programming Basics]]
	- [[11.2 Constructs]]
	- [[11.3 Structured Programming]]
- ### [[12 Software Development]]
	- [[12.1 Program Development Life cycle]]
	- [[12.2 Program Design]]
	- [[12.3 Program Testing and Maintenance]]

## Papers
### Papers to be done
```dataview
table QP, MS, tags[1] as paper
From #Paper and #CS 
where !Done and length(tags) != 1
```

### Papers Done
```dataview
table DateDone, tags[1] as paper, MyScore*100/FullScore as Score
From #Paper and #CS 
where done
sort DateDone ASC
```

## questions
```dataview
TABLE mark, content, difficulty
From #Question and #CS
```
