# How to Run the Library Demo

## Prerequisites

- JDK 17 or later (`java` and `javac` must be on PATH)
- Python 3.9 or later
- No Maven, Gradle, IDE, or third-party library is needed

## Run

From the repository root:

```
python3 run.py demo
```

On Windows, use `py -3 run.py demo` if that is how you run Python 3.

## What the demo does

The runner compiles the Java sources into a temporary directory and runs a small
library-loan scenario on a fixed date (2026-09-01). It prints the student and
faculty borrowing limits, searches the catalog for "git", lets a student borrow
a book and prints the loan receipt and due date, then returns the book and shows
the return fee and the number of active loans.