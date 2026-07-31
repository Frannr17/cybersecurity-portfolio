# Update a File Through a Python Algorithm

## Overview

This project demonstrates how Python can automate security administration tasks by maintaining an IP allow list. The algorithm reads authorized IP addresses from a file, removes unauthorized entries based on a remove list, and safely updates the original file.

---

## Skills Demonstrated

- Python Programming
- File Handling
- Automation
- Data Processing
- Algorithm Development
- Access Control

---

## Tools & Technologies

- Python

---

## Frameworks / Concepts

- Automation
- Secure File Management
- Access Control

---

## Project Description

This project automates the maintenance of an IP allow list used to control access to a restricted network. The algorithm reads the current allow list, compares it against a predefined remove list, removes unauthorized IP addresses, and writes the updated list back to the original file.

---

## Objectives

- Read an external text file.
- Convert data into a list.
- Iterate through multiple IP addresses.
- Remove unauthorized entries.
- Update the original file automatically.

---

## Methodology

The solution uses Python's `with` statement to safely open files, the `.read()` method to import file contents, `.split()` to convert text into a list, a `for` loop combined with conditional statements to identify unauthorized IP addresses, `.remove()` to delete them, and `.join()` with `.write()` to overwrite the original file.

---

## Results

Successfully automated the process of updating the IP allow list while reducing manual administrative work and minimizing the possibility of human error.

---

## Key Takeaways

Python is an effective language for automating repetitive security administration tasks. Automating access list maintenance improves efficiency, consistency, and security.
