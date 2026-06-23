# java_fundamentals_test
java syntax , problem solving and exam practise

# 🚀 Software Engineering Deep Dive Challenge
> A mixed theory + implementation repository covering software engineering foundations and Java development.

---

# 📚 Overview

This repository is divided into:

- 🧠 50% Theory
- 💻 50% Coding (Java + JUnit)

Goal:
Develop understanding of software engineering concepts while implementing practical solutions using Java.

---

# Structure

```
software-engineering-deep-dive/
│
├── README.md
│
├── theory/
│   ├── version-control.md
│   ├── language-levels.md
│   ├── build-tools.md
│   ├── syntax-coding.md
│   └── oop.md
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── challenges/
│   │
│   └── test/
│       └── java/
│
└── pom.xml
```

---

# 🧠 THEORY SECTION (50%)

---

# 1. Version Control

## Questions

### Beginner
1. What problem does version control solve?

2. Explain:
- Working Directory
- Staging Area
- Repository

3. Difference:
```
git fetch
git pull
git clone
```

---

### Intermediate

4. Explain branching strategy:

- main
- develop
- feature
- hotfix

5. Merge vs Rebase

6. What happens internally during:

```bash
git commit
```

---

### Advanced

7. Explain:

```bash
git reset
git revert
git cherry-pick
```

8. Describe Git object types:
- Blob
- Tree
- Commit
- Tag

---

# 2. Low-Level vs High-Level Languages

---

## Compare:

| Feature | Low-Level | High-Level |
|----------|----------|-----------|
| Abstraction | | |
| Memory | | |
| Speed | | |
| Portability | | |

---

### Discussion

1. Why is Java considered high-level?

2. Explain:
- Compilation
- Interpretation
- JVM

3. What tradeoffs exist between:
- C
- Java
- Python

4. Why are operating systems often written in C?

---

# 3. Build Tools

---

Explain:

### Maven

Lifecycle:
```
validate
compile
test
package
verify
install
deploy
```

---

### Gradle

Answer:

- Why is Gradle faster?
- Dependency Resolution
- Build Automation

---

Challenge:

Create commands for:

```bash
mvn clean install
```

Explain every stage.

---

# 4. Syntax & Coding

---

Questions:

1. Strong vs Weak typing

2. Static vs Dynamic typing

3. Compiler vs Interpreter

4. Explain:

```java
final
static
abstract
interface
```

---

# 5. Object-Oriented Programming

---

Explain:

### Four Pillars

- Encapsulation
- Abstraction
- Inheritance
- Polymorphism

---

Theory Challenge:

Design a banking system.

Identify:

Classes

Interfaces

Relationships

Composition

Inheritance

---

# 💻 CODING SECTION (50%)

---

# Challenge 1 — Git Commit Simulator

Create:

```java
class Commit
```

Functions:

```java
addFile()

commit()

undo()

history()
```

Rules:

- Max 10 staged files
- Cannot commit empty changes
- Commit IDs auto generated

---

## JUnit Tests

```java
@Test
void shouldCreateCommit()
```

```java
@Test
void shouldRejectEmptyCommit()
```

```java
@Test
void shouldUndoCommit()
```

---

# Challenge 2 — Language Benchmark

Create:

```java
interface Language
```

Methods:

```java
execute()

memoryUsage()
```

Implement:

```java
JavaLanguage
CLanguage
PythonLanguage
```

---

JUnit:

```java
@Test
void shouldMeasureExecution()
```

```java
@Test
void shouldCompareLanguages()
```

---

# Challenge 3 — Build Tool Simulator

Build:

```java
BuildPipeline
```

Stages:

```java
validate()
compile()
test()
packageApp()
deploy()
```

Rules:

- Stage cannot skip previous stage

---

JUnit

```java
@Test
void shouldCompileAfterValidate()
```

```java
@Test
void shouldRejectDeployWithoutCompile()
```

---

# Challenge 4 — Syntax Validator

Input:

```java
public class Test {
```

Output:

```text
Syntax Error
```

Features:

- Brackets
- Semicolons
- Variables

---

JUnit

```java
@Test
void shouldDetectMissingBracket()
```

```java
@Test
void shouldPassValidCode()
```

---

# Challenge 5 — OOP Battle Arena ⚔️

Build:

```java
abstract class Character
```

Implement:

```java
Mage
Warrior
Tank
```

Rules:

- Attack
- Defend
- Heal
- Level System

---

JUnit

```java
@Test
void warriorShouldAttack()
```

```java
@Test
void mageShouldUseMana()
```

```java
@Test
void tankShouldReduceDamage()
```

---

# 🏆 FINAL BOSS

Build a complete system:

```text
Developer Simulator
```

Features:

- Uses Git
- Compiles Project
- Runs Tests
- Tracks Performance
- OOP Architecture

Constraints:

- SOLID Principles
- 80% Test Coverage
- Maven
- Java 21

---

# Submission

Requirements:

```bash
mvn clean test
```

Passing:

✅ All tests green

---

# Stretch Goals

- CI/CD
- Docker
- GitHub Actions
- Mutation Testing
- Design Patterns

---

# Outcome

After completing this repository you should understand:

✔ Version Control  
✔ Programming Language Abstractions  
✔ Build Systems  
✔ Syntax & Compilation  
✔ Object-Oriented Design  
✔ Automated Testing
