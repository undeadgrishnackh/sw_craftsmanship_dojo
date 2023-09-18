# 🟡 Yellow Belt 🟡 Lesson 10: Continuous Build & Quality Gate Part I

## 📚 Homework Showcase

- Daily kata awareness moment --> showcase
- 🙋‍♂️ Did you use _Conventional_ Commit at every 🔴Red/🟢Green/♻️Refactor?
- 🙋‍♂️ Did you stick to a Cyclomatic Complexity to <= 4?
- 🙋‍♂️ Did you clean up all the Linter / CheckStyle smells?
- 🙋‍♂️ Did the quality enforcer reduce the _accidental complications_ in the
  codebase?
- 🙋‍♂️ Did the complexity of your 🤷‍♂️ DUMMIES and 🎭 STUBS decreased?

---

## 👨🏻‍🏫 Recap

- Readability 🤓 VS 🧠 Understandability
- 🤔 Has Cyclomatic complexity an impact on Coverage?
- Code quality gates:
  - [Git Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/)
  - List of
    [Git Conventional types](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13#types)
  - Linter
  - Check Style
- 🤔 How do you force a new developer to use a local quality gate?

## 📚 Theory and Immediate 🏋️ Practice: Improve Our Local Quality Gate 🤖

- 📚 [Git hooks 🤖](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
- 🏋🏻‍♂️ Install Git hooks:
  - 🐍 [pre-commit (Python)](https://pypi.org/project/python-githooks/)
  - 🛡️ [husky (JS)](https://typicode.github.io/husky/)
- 🏋🏻‍♂️ Configure your local quality gate:
  - 1️⃣ Linter
  - 2️⃣ CheckStyle
  - 3️⃣ Conventional Commit

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
   - 👉 Local Quality Gate automation via git hooks
   - 👉 Remote Quality Gate in the CI Pipeline (CB phase)
   - Prioritize the technical debt into `TECHDEBT.md`
   - Apply the refactor _Boy Scout rule_
   - Keep a deeper clean code posture to let the architecture emerge
   - Check the _accidental complications_. Is it under control and close to
     ZERO?
   - Rate your code as it's a best-seller book... 5⭐️ or 🗑️?
