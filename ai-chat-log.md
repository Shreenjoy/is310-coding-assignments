# AI Chat Log

A log of prompts I used with AI tools for IS310, plus what I got back and what
I thought of it.

## Assignment 1: Command Line and Git Setup

**Tool used:** Claude

**Prompt:**

> How can I check if my directory was created in my terminal?

**Response summary:** Suggested `ls` to list directory contents and `pwd` to
print the full working path, and explained the difference between them.

**Reflection:** Fast and correct, but it's the same answer that was already on
the course cheatsheet. The chatbot was more useful later when I hit a
`Repository not found` error on `git push`, where it narrowed the cause down to
the remote repo not existing yet rather than an auth problem.

**Prompt:**

> How do I create a GitHub repo and push to it in one command?

**Response summary:** Pointed me to the GitHub CLI, specifically
`gh repo create <name> --public --source=. --remote=origin --push`, which
creates the remote repo and pushes the local one in a single step.

**Reflection:** This actually saved time over the browser workflow, and
`gh auth login` also cleared up the credential issue so I never had to make a
personal access token.
