---
icon: lucide/rocket
hide: 
    - navigation
---

# Get Started

**Welcome to Shell & CLI Fundamentals. This page will get you set up and explain how the workshop works before you dive in.**

---

## Learning 'Linux'

The terminal is the most powerful skill any user of a Unix-like operating system can learn. Instead of being overwhelemed by the steep learning curve, this workshop teaches you the basics **interactively** to help understand why and how the terminal, shell and command-line work harmoniously together. You will learn the basics through different chapters which walk you through many different concepts. 

Too many users (and even developers) spend years avoiding the terminal. This workshop aims to fix that Learn to navigate files and directories, configure your system enviornment, and make use of CLI tools. 

***No prior experience is needed. Just a computer and a willingness to type.***

---

## Prerequisites

- A computer running Linux, macOS, or Windows. Running another OS? Why are you here.
- No prior command line experience required
- Patience

---

## Setting Up Your Environment

You'll need a terminal to follow along. Here's how to open one on each operating system:

=== "Linux"

    I refuse to accept that you do not know the terminal. Search for **Terminal** in your applications, or press ++ctrl+alt+t++ on most distributions.

    Verify your shell:
    ```bash
    echo $SHELL #(1)!
    /bin/bash #(2)!
    ```

    1. The `echo` command prints the value of the `$SHELL` variable.
    2. This is the expected output - your shell path. You might see `/bin/zsh` instead - both are fine.

=== "macOS"

    Open **Terminal** from Applications &#8594; Utilities, or press ++cmd+space++ and search for Terminal.

    Verify your shell:
    ```bash
    echo $SHELL #(1)!
    /bin/bash #(2)!
    ```

    1. The `echo` command prints the value of the `$SHELL` variable.
    2. This is the expected output - your shell path. You might see `/bin/zsh` instead - both are fine.

=== "Windows"

    Windows users will begin with the **Command Prompt**, but will transfer to WSL with instructions later to follow along with this tutorial. Search for Command Prompt and open as Administrator.

    Verify your shell:
    ```console 
    C:\> echo %COMSPEC%
    C:\Windows\System32\cmd.exe
    ```

    !!! note
    
    	This shows the path to your default shell. You'll move to WSL later in the tutorial to follow along with bash commands.

!!! tip
    Increase your font size, you'll be staring at it a lot.

---

## How to Use This Tutorial

### Type the commands

**DO NOT COPY AND PASTE**. Type every command out yourself and it will feel slow. You need to start building muscle memory with your fingers. It is genuinely a real thing with the command-line.

### Reading the formatting

Throughout this tutorial you'll see:

**Code blocks** - commands to run in your terminal:
```bash
ls -la
```

**Inline code** - command names, flags, and file paths mentioned in text, like `ls`, `cd`, or `pwd`

**Keyboard shortcuts** - keys to press, like ++ctrl+c++ or ++tab++

**Admonitions** - callout boxes with extra context:

!!! note
    Extra context.

!!! abstract
    A summary or overview of what is covered in this section.

!!! tip
    A helpful tip or best practice.

!!! warning
    These will not necessarily break anything, but ignoring them can lead to unexpected results.

!!! danger
    Read carefully before running the command.

!!! info
    Additional information that provides useful context without being critical to understanding.

!!! success
    Confirms you have completed a step or exercise correctly.

!!! question
    To test your understanding. Try to answer before moving on, if you cannot, review the section again.

!!! failure
    A common mistake or error you might encounter, and how to fix it.

!!! example
    A worked example showing a real use case of the concept just covered.

!!! quote
    A quote from a manual page, documentation, or other reference material.

### Expected output

When a command produces output, you will see it shown:

```bash
$ echo "hello"
hello
```

The `$` represents your terminal prompt, do not type it. Everything after it is the command. Lines without `$` are the expected output.

### If something goes wrong

- Typically Press ++ctrl+c++ to cancel a running command
- Typically Press ++ctrl+z++ to suspend a process
- Type `exit` to close a terminal session

---

## What to Expect

Each section of the tutorial will flow with a similar structure:

1. **Introduction** - what the topic is and why it matters
2. **Concepts** - the theory behind it, kept brief and practical
3. **Commands** - the key commands with examples
4. **Walkthrough** - exercises to practice
5. **Tips** - best practices and common gotchas
6. **Questions** - to check comprehension before moving on

---

[Start the Tutorial :lucide-arrow-right:](workshop/terminalshells/index.md){ .md-button .md-button--primary }

<!-- Acronyms -->
*[CLI]: Command-Line Interface
*[stdin]: Standard Input
*[stdout]: Standard Output
*[stderr]: Standard Error
*[WSL]: Windows Subsystem for Linux