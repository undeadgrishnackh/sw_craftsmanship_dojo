# 🟡 Yellow Belt 🟡 Lesson 9: Clean Code: Refactor, Linter, Git Semantics

## 📚 Homework Showcase

- Daily kata awareness moment --> showcase 🤷‍♂️ DUMMIES and 🎭 STUBS
- 🙋‍♂️ Did you improve the code ISOLATION in your tests via 🤷‍♂️ DUMMIES and 🎭
  STUBS?
- 🙋‍♂️ Did you find it easier to design the UAT via the Doubles?
- 🙋‍♂️ Did you create the tests in less than 30 seconds?
- 🙋‍♂️ Did the Doubles reduce the _accidental complications_ in the codebase?

---

## 📚 Theory with Immediate 🏋🏻‍♂️ Practice: Advanced Refactoring

Scenario: yellow belt graduation test code review via MOB programming.

> MOB programming is a collaborative approach to software development in which a
> group of developers work **together** in real time on one task

- 📚 Readability 🤓 VS 🧠 Understandability
  - 📚 Flow & WTF = 🤓 Readability
  - 📚 Code cyclomatic complexity = 🧠 Understandability
  - 🏋🏻‍♂️ Install the Cyclomatic complexity plugin
  - 🏋🏻‍♂️ Scan the codebase with [SonarCloud.io](https://sonarcloud.io/)
  - 🏋🏻‍♂️ Scan the codebase with [CodeScene.io](https://codescene.io/)
  - 📚 Brain cognitive processes:
    - When we code --> 🤯 divergent thinking
    - When we read --> 🎯 laser focus on the flow
  - 🏋🏻‍♂️ Review your code as a new team member. Where do you start? 🥺
    - 👨🏻‍🏫 Suggested reading
      [The Unicorn Project](https://www.oreilly.com/library/view/the-unicorn-project/9781098124175/)
- 📚 Code quality gates
  - How do we measure code quality?
  - 🏋🏻‍♂️ Install a Linter (ESLint, PyLint, et.)
  - 🏋🏻‍♂️ Install a Code Style Checker --> (Prettier, Black, CheckStyle, et.)
  - 📚 Code smells --> A super fast introduction to
    [Refactoring for Software Design Smells](https://learning.oreilly.com/library/view/refactoring-for-software/9780128013977/)
  - 🤔 How do we prevent smells from being pushed into our remote? 🤬🤬🤬🤬
- 📚 Git workflow, commit & hooks
  - 🤔 Is our git history highlighting the code milestones?
  - 📚
    [Git semantic](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
  - 📚 Future reading
    [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
  - 🤔 Why conventional commits are important:
    - How do you release your product?
    - Do you version it?
    - Do you share a ChangeLog at every release?
    - How much time does it take to prepare all this stuff?

---

## 📚 Homework

1. 5+ katas with notes.
2. Improve your daily drill:
   - Only 1 🍅 Pomodoro
   - Use the 📝 properly
   - Organize the `BACKLOG.md` by ATDD and incremental complexity
   - Focus on improving your tests using 🤷‍♂️ DUMMIES and 🎭 STUBS
   - 👉 _Conventional_ Commit at every 🔴Red/🟢Green/♻️Refactor
   - 👉 Reduce the Cyclomatic Complexity to <= 4
   - 👉 Ensure your codebase doesn't raise any Linter / CheckStyle smells
   - Prioritize the technical debt into `TECHDEBT.md`
   - Apply the refactor _Boy Scout rule_
   - Keep a deeper clean code posture to let the architecture emerge
   - Check the _accidental complications_. Is it under control and close to
     ZERO?
   - Rate your code as it's a best-seller book... 5⭐️ or 🗑️?
