---
icon: lucide/rocket
---

# Get Started

Welcome to Shell & CLI Fundamentals. This page will get you set up and explain how the tutorial works before you dive in.

---

## What This Tutorial Is About

This is a hands-on introduction to the command line, shells, and Unix-like systems. By the end you'll be comfortable navigating a filesystem, managing files and permissions, running programs, piping commands together, installing software, and writing basic shell scripts.

No prior experience is needed. Just a computer and a willingness to type.

---

## Prerequisites

- A computer running Linux, macOS, or Windows with WSL
- No prior command line experience required
- Curiosity and patience

---

## Setting Up Your Environment

You'll need a terminal to follow along. Here's how to open one on each operating system:

=== "Linux"

    You already have a terminal. Search for **Terminal** in your applications, or press ++ctrl+alt+t++ on most distributions.

    Verify your shell:
    ```bash
    echo $SHELL
    ```

=== "macOS"

    Open **Terminal** from Applications → Utilities, or press ++cmd+space++ and search for Terminal.

    We recommend [iTerm2](https://iterm2.com) as a more feature-rich alternative.

    Verify your shell:
    ```bash
    echo $SHELL
    ```

=== "Windows"

    Windows requires WSL (Windows Subsystem for Linux) to follow along with this tutorial.

    1. Open PowerShell as Administrator
    2. Run:
    ```powershell
    wsl --install
    ```
    3. Restart your computer
    4. Open **Windows Terminal** and select Ubuntu

    Verify your shell:
    ```bash
    echo $SHELL
    ```

!!! tip "Recommended terminal settings"
    Increase your font size to at least 14px — you'll be staring at it a lot. A monospace font like JetBrains Mono or Fira Code makes a big difference for readability.

---

## How to Use This Tutorial

### Actually type the commands

Don't copy and paste. Type every command out yourself. It feels slower but your fingers need to learn this too — muscle memory is a real thing with the command line.

### Reading the formatting

Throughout this tutorial you'll see:

**Code blocks** — commands to run in your terminal:
```bash
ls -la
```

**Inline code** — command names, flags, and file paths mentioned in text, like `ls`, `cd`, or `~/.bashrc`

**Keyboard shortcuts** — keys to press, like ++ctrl+c++ or ++tab++

**Admonitions** — callout boxes with extra context:

!!! tip
    A helpful tip or best practice.

!!! warning
    Something to be careful about.

!!! danger
    Something that could cause data loss or serious issues.

!!! note
    Extra context or background information.

!!! question "Comprehension check"
    Questions at the end of sections to test your understanding.

### Expected output

When a command produces output, you'll see it shown like this:

```bash
$ echo "hello"
hello
```

The `$` represents your terminal prompt — don't type it. Everything after it is the command. Lines without `$` are the expected output.

### If something goes wrong

- Press ++ctrl+c++ to cancel a running command
- Press ++ctrl+z++ to suspend a process
- Type `exit` to close a terminal session
- Use `man <command>` or `<command> --help` to read the manual for any command

---

## What to Expect

Each section of the tutorial follows the same structure:

1. **Introduction** — what the topic is and why it matters
2. **Concepts** — the theory behind it, kept brief and practical
3. **Commands** — the key commands with examples and expected output
4. **Walkthrough** — a step-by-step exercise to practice
5. **Tips** — best practices and common gotchas
6. **Comprehension questions** — to check your understanding before moving on

Work through the sections in order — each one builds on the previous.

---

## Ready?

[Start the Tutorial :lucide-arrow-right:](workshop/01-the-command-line/index.md){ .md-button .md-button--primary }
