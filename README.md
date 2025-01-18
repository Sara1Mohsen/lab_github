![Screenshot from 2025-01-17 09-49-17](https://github.com/user-attachments/assets/ce5cf8e1-9a2b-4441-a558-042f55ad6b9f)


delete branch local ---> git branch -d test

delete branch remotly ---> git push origin --delete test

////////////////////////////////////////////////////////
# Annotated Tags vs Lightweight Tags

## Annotated Tags
- **Description**: Annotated tags store additional metadata about the tag, such as:
  - The tagger’s name and email.
  - A tagging message.
  - The date and time of the tag.
  - Optionally, a GPG signature for verification.
- **Usage**: Suitable for releases or when you want to provide more context about the tagged commit.
- **Creation Command**:
  ```bash
  git tag -a <tagname> -m "Tag message"

## Lightweight Tags
- A **lightweight tag** is a simple reference to a specific commit in Git.
- It acts as a pointer to a commit, without any additional metadata.
- Unlike annotated tags, it doesn’t store information such as the tagger's name, date, message, or a GPG signature.

## use Lightweight Tags
- For **temporary tags** that don’t require metadata or context.
- When you need a quick and simple way to mark a commit.
```bash
git tag <tagname>
///////////////////////////////////////////////////////////////
# How to List Tags

## Overview
Git provides commands to view all tags in a repository. Tags can be listed with basic or detailed information.

---

## Basic Tag Listing
To view all tags in the repository:
```bash
git tag
/////////////////////////////////////////////////////////////////////


