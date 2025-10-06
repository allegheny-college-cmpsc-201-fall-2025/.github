![CMPSC 201 word cloud](../assets/allegheny-college-cmpsc-201-fall-2025.png)

# CMPSC 201: Programming Languages (Fall 2025)

> A study of the fundamental concepts that arise in different programming
language paradigms. Students learn how programming languages are designed and
implemented, and how these factors affect the overall usability, performance,
and effectiveness of computer software. Participating in hands-on activities
that often require teamwork, students gain experience in leveraging the styles
and features of programming languages to implement and evaluate correct and
efficient computer software. During a weekly laboratory session, students use
state-of-the-art technology to complete projects, reporting on their results
through both written documents and oral presentations. Students are invited to
use their own departmentally approved laptop in this course; a limited number of
laptops are available for use during class and lab sessions.

## Office Hours

Given the relatively small population of our course, appointments will not be
necessary; i.e., **all office hours are walk-in only**. That means first come,
first serve.

| Day | Time          |
| :-- | ------------: |
| Wed | 5p - 6p       |
| Fri | 6p - 8p       |

## Textbook: *Crafting Interpreters*

No textbook purchases are required for this course. Rather, this course utilizes
content from the first ten chapters of Robert Nystrom's
[*Crafting Interpreters*](https://craftinginterpreters.com/contents.html), which
is available for free in a webbook format.

## Course Calendar: The Road Ahead

| Week Starting            | Type      | Theme                    | Reading    |
| ------------------------ | --------- | ------------------------ | ---------- |
| 8/26 (no lab)            | Commit    | Orientation              | Chapter 1  |
| 9/1 (no lab)             | Commit    | Parts of a Language      | Chapter 2  |
| 9/8                      | Commit    | Enter Lox                | Chapter 3  |
| 9/15                     | Build     | Language Toy Box         | N/A        |
| 9/22                     | Commit    | Scanning                 | Chapter 4  |
| 9/29                     | Commit    | Grammars                 | Chapter 5  |
| 10/6 (no TH class)       | Commit    | Parsing                  | Chapter 6  |
| 10/13                    | Build     | Mission Im-parse-ible    | N/A        |
| 10/20                    | Commit    | Expressions              | Chapter 7  |
| 10/27                    | Commit    | Statements               | Chapter 8  |
| 11/3 (no TU class)       | Commit    | Control Flow             | Chapter 9  |
| 11/10                    | Build     | Locking in Lox           | N/A        |
| 11/17                    | Commit    | Functions                | Chapter 10 |
| 11/24 (no TH class)      | Working   | N/A                      | N/A        |
| 12/1                     | Working   | N/A                      | N/A        |
| 12/8 (exam @ TU, 9am)    | Release   | N/A                      | N/A        |

## Current Week Deliverables (10/6)

- **Discord Discussion:** *by Wednesday @ 11:59pm*, post a novel insight
  (meaning something that one of your peers has not already shared) to this
  week's Discord thread about Nystrom's parsing code snippets

- **Team Deliverable:** *by Tuesday @ 12:14pm*, submit a project charter for
  next week's build project which includes:

  - Role assignments: one captain (responsible for the `project-charter.md`
    file) and two presenters (responsible for the `project-reflection.md`)

  - At least two intermediate deadlines per team member; each deadline should
    note the specific individuals responsible for the deadline as well as the
    date the task should be achieved by

  - A performance review schedule noting who is being reviewed on which days
    next week, based on this cadence:

    - 3/4 team members on Monday (3 for Cooler, 4 for Fornite)

    - 2 team members on Tuesday

    - 1 team member on Thursday

  - The selection of five linting rules that the team will tackle from the below
    menu:

    - A: Unused imports - import statements never used/referenced

    - B: Variable shadowing - variable names inside a function that reuse an
      outer scope variable name

    - C: Unreachable code - code after a `return`, `break`, or `continue` that
      can't be accessed

    - D: Empty blocks - `if`, `for`, and `while` statements that only contain
      `pass`

    - E: Long functions - functions that contain more than *N* statements

    - F: Naming conventions - enforcing `snake_case` for variables & functions

    - G: Magic numbers - "bare" constants used instead of named variables

    - H: Docstring enforcement - require a docstring for all functions
    
    - I: Too many parameters - detect functions with more than *N* arguments

    - J: Nested control structures - detect nesting that goes deeper than *N*
      levels

- **Individual Deliverable:** *by Wednesday @ 5:59pm*, demonstrate a working
  version of your team's Lox parser for the instructor and add at least three
  comments with your initials to the code for `Parser`, `GenerateAst`, or
  `AstPrinter`

- **Reflection Entry:** *by Wednesday @ 11:59pm*, within your individual
  repository, add a Markdown (`.md`) file (no other file types will be counted)
  with a 200 word (minimum) response to the following prompt:
  
  > Review your team's plan for tackling next week's build project. To your own
  > understanding, what will the final deliverable look like? How will it
  > logically function?

- **Mapmaking Task:** *by Wednesday @ 11:59pm*, within your individual
  repository, add a `.png` image file (no other file types will be counted)
  exported from [excalidraw](https://excalidraw.com/) that visualizes how the
  Lox `Parser` works; this should connect to the maps for scanning and grammars
  (do not clear your canvas) and should also use at least ten shapes/entities
  to illustrate the `Parser`
