# NumPyMaster
A client-side app to learn NumPy interactively. It runs Python in-browser via Pyodide and Monaco Editor—no backend needed! Features 50 gamified tasks, AST auto-grading, and IndexedDB progress saving.

# NumPy Masterclass

An interactive web app to teach Python's NumPy library through 50 gamified exercises.

## Tech Details
* **Zero Backend:** Runs Python 3.11 entirely in-browser using **Pyodide** (WebAssembly) and Web Workers.
* **Pro Workspace:** Uses **Monaco Editor** for a VS Code-like coding experience.
* **Smart Auto-Grader:** Validates code in real-time using hidden `assert` statements and AST checks to ensure correct method usage.
* **Gamification:** Earn coins, unlock challenges, and save progress locally via **IndexedDB**.
