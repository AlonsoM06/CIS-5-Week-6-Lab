# Lab 6 · Decisions

**Week 06 · Conditionals**  
**Theme:** The program chooses  
**Type:** Lesson week


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** _add your link here_


## Scenario
An `if` statement chooses which block runs based on a true or false condition. Build a grade or eligibility tool with real thresholds, and test the edges.

## Goals
- `if` / `else if` / `else` with braces on every branch
- At least one `&&` or `||` in a real condition
- Test the edges (just-below, exactly-on, and a wild value)
- Push + short demo + Canvas

## Starter
Use `main.cpp`. Put your name in the file-top comment.

## Environment
VS 2022 · **GitHub Codespaces** · Replit · library machines

## Procedure
1. Write the rules on paper first (A ≥ 90, B ≥ 80, … — or your own)
2. Implement with braces. Order the tests from the top
3. Add one combined condition (`&&` or `||`) you can read aloud
4. Run 89, 90, and 100 (or your edges). Fix what lies
5. Commit, push, short demo, Canvas

## Sample output
```
Score 0-100: 83
Letter: B
```

A second run:
```
Score 0-100: 90
Letter: A
```

## Definition of done
- Compiles with zero errors
- Multi-way decision + one combined condition
- Edges tested (show at least two runs in the demo)
- Repo + short demo + Canvas

## Rubric (100)
| Criterion | Pts |
|-----------|----:|
| Runs correctly on a supported path | 40 |
| Meets prompt requirements | 30 |
| Clear outcome messages | 15 |
| GitHub + short demo video | 15 |

## Scope fence
No `goto`. Keep nesting shallow. `switch` is optional, not required.

## Tips
- `=` assigns. `==` compares
- If 70 comes before 90, an A never arrives
- Braces even for one line — the next edit will add a second line

## Help (`/ring`)
After a real try, include: goal · what you tried · exact error · screenshot/repo · OS + tool.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
