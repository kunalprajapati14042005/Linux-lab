# 🧪 Linux Lab

This repository contains Linux lab experiments along with their scripts and command references.

---

# 🧪 Experiment 1: Advanced Bash Scripting

## 🎯 Aim
To implement a comprehensive Bash script that handles user input, arithmetic operations, and complex conditional logic using numerical comparison operators.

---

## ⚙️ Procedure

### 1. Create File
```bash
nano experimental_script.sh

### 2. Script Implementation

```bash
#!/bin/bash

echo "this is my first bash"

# taking input
echo "enter name"
read name1

# add operation
echo "enter a number"
read a
echo "enter a number"
read b
var=$((a+b))
echo $var

# number comparison
echo "enter a number"
read x
echo "enter a number"
read y

if [ $x -gt $y ]
then
    echo "x is greater than y"
elif [ $x -lt $y ]
then 
    echo "x is less than y"
elif [ $x -eq $y ]
then
    echo "x is equal to y"
fi
Operator,Description
-gt,Greater Than
-lt,Less Than
-eq,Equal To
$((...)),Arithmetic Expansion
