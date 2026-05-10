# Learn Playwright - Batch 2X

> **A structured learning journey from JavaScript fundamentals to advanced Playwright automation testing.**

---

## 📋 Table of Contents

- [About This Repository](#about-this-repository)
- [Learning Progress](#learning-progress)
- [Chapter 1: JavaScript Basics](#chapter-1-javascript-basics)
- [Chapter 2: JavaScript Concepts](#chapter-2-javascript-concepts)
- [Chapter 3: Identifiers & Literals](#chapter-3-identifiers--literals)
- [Upcoming: Playwright Learning Roadmap](#upcoming-playwright-learning-roadmap)
- [VS Code Shortcuts](#vs-code-shortcuts)
- [How to Run](#how-to-run)
- [Resources](#resources)

---

## About This Repository

This repository documents the complete learning path for **Playwright Test Automation** starting from JavaScript fundamentals. It is organized into progressive chapters, starting with core JavaScript concepts and gradually moving into Playwright-specific topics.

Each chapter contains hands-on `.js` files with comments and examples to reinforce learning through practice.

---

## Learning Progress

| Chapter | Topic | Status |
|---------|-------|--------|
| 1 | JavaScript Basics | ✅ Completed |
| 2 | JavaScript Concepts | ✅ Completed |
| 3 | Identifiers & Literals | ✅ Completed |
| 4 | Data Types & Operators | 🔄 Upcoming |
| 5 | Control Flow & Loops | 🔄 Upcoming |
| 6 | Functions & Scope | 🔄 Upcoming |
| 7 | Arrays & Objects | 🔄 Upcoming |
| 8 | ES6+ Features | 🔄 Upcoming |
| 9 | Async JavaScript | 🔄 Upcoming |
| 10 | Playwright Setup & Basics | 🔄 Upcoming |
| 11 | Playwright Core Concepts | 🔄 Upcoming |
| 12 | Advanced Playwright | 🔄 Upcoming |

---

## Chapter 1: JavaScript Basics

**Folder:** `chapter_01_Basics/`

### Topics Covered

| File | Topic | Description |
|------|-------|-------------|
| `01_Basics.js` | Introduction to JS | `console.log()`, variable declaration with `let` |
| `02_JS.js` | Loops & Functions | `for` loop, function declaration and calling |
| `03_JS_Commands.js` | Node.js `process` object | Checking platform (`win32`), architecture (`x64`), Node version |
| `04_HotCode.js` | Function Performance | Loop-based function calls to understand execution flow |

### Key Takeaways
- JavaScript runs via Node.js on the server-side
- `console.log()` is the primary debugging tool
- Variables can be declared using `let`
- Functions are reusable blocks of code
- Node.js provides the `process` object for system-level information

---

## Chapter 2: JavaScript Concepts

**Folder:** `chapter_02_Javascript_Concepts/`

### Topics Covered

| File | Topic | Description |
|------|-------|-------------|
| `05_JS_Basics.js` | Variable Re-assignment | Using `var`, re-assigning values to variables |

### Key Takeaways
- `var` allows variable declaration and re-assignment
- Variables in JavaScript are dynamically typed
- Understanding the difference between declaration and assignment is crucial

---

## Chapter 3: Identifiers & Literals

**Folder:** `chapter_03_Identifier_Literals/`

### Topics Covered

| File | Topic | Description |
|------|-------|-------------|
| `06_Identifier_Rules.js` | Identifier Rules | Valid/invalid identifier naming, `$` and `_` usage |
| `07_Identifier_Part2.js` | Naming Conventions | camelCase, PascalCase, snake_case, SCREAMING_SNAKE_CASE, Hungarian Notation |
| `08_Comments.js` | Comments in JS | Single-line `//`, multi-line `/* */`, and JSDoc-style `/** */` comments |
| `js_identifier_rules.js` | Comprehensive Rules | Complete guide to JavaScript identifier rules with examples |

### Key Takeaways

#### Identifier Rules
- Must begin with a **letter**, **underscore `_`**, or **dollar sign `$`**
- Subsequent characters may include digits
- **Cannot start with a digit** (e.g., `1stPlace` is invalid)
- **Cannot use reserved keywords** (e.g., `class`, `const`, `function`)
- Identifiers are **case-sensitive** (`name` ≠ `Name`)
- Unicode characters and escape sequences are allowed
- Cannot contain spaces, hyphens, or special characters (except `_` and `$`)

#### Naming Conventions

| Convention | Example | Use Case |
|------------|---------|----------|
| **camelCase** | `userName`, `totalPrice` | Variables & Functions |
| **PascalCase** | `UserProfile`, `ShoppingCart` | Classes & Constructors |
| **snake_case** | `user_name`, `total_price` | General naming (less common in JS) |
| **SCREAMING_SNAKE_CASE** | `MAX_SIZE`, `API_KEY` | Constants |
| **Hungarian Notation** | `strName`, `bActive`, `nCount` | Type-prefixed (older style) |

#### Comments
- `//` — Single-line comment
- `/* ... */` — Multi-line comment
- `/** ... */` — JSDoc / Documentation comment

---

## Upcoming: Playwright Learning Roadmap

### Phase 1: JavaScript Mastery (Foundation)

Before diving into Playwright, the following JavaScript topics will be covered:

| Day | Topic | Details |
|-----|-------|---------|
| 1-2 | Data Types & Operators | Strings, Numbers, Booleans, Null, Undefined, Symbols, BigInt; Arithmetic, Comparison, Logical, Assignment operators |
| 3-4 | Control Flow & Loops | `if/else`, `switch`, `for`, `while`, `do...while`, `break`, `continue` |
| 5-6 | Functions Deep Dive | Function declarations, expressions, arrow functions, parameters, return values, IIFE |
| 7-8 | Arrays & Array Methods | `map()`, `filter()`, `reduce()`, `forEach()`, `find()`, `sort()`, spread operator |
| 9-10 | Objects & JSON | Object literals, properties, methods, destructuring, JSON parsing/stringifying |
| 11-12 | ES6+ Features | `let`/`const`, template literals, destructuring, default parameters, rest/spread, modules |
| 13-14 | Async JavaScript | Callbacks, Promises, `async/await`, `fetch` API, error handling |
| 15 | Error Handling & Debugging | `try/catch/finally`, throwing errors, debugging techniques |

### Phase 2: Playwright Fundamentals

| Day | Topic | Details |
|-----|-------|---------|
| 16 | Playwright Setup | Installation, project initialization, configuration (`playwright.config.ts`) |
| 17 | First Test | Writing and running your first Playwright test, understanding test structure |
| 18 | Locators | CSS selectors, XPath, text selectors, role-based locators, chaining locators |
| 19 | Actions | Click, fill, type, hover, focus, drag-and-drop, scroll |
| 20 | Assertions | Built-in assertions (`expect`), page assertions, element state assertions |
| 21 | Handling Inputs | Text inputs, checkboxes, radio buttons, dropdowns, file uploads |
| 22 | Navigation | `goto()`, `goBack()`, `goForward()`, `reload()`, handling new pages/tabs |

### Phase 3: Playwright Intermediate

| Day | Topic | Details |
|-----|-------|---------|
| 23 | Waiting Strategies | Auto-waiting, explicit waits, `waitForSelector()`, `waitForLoadState()` |
| 24 | Frames & Windows | Handling iframes, pop-ups, multiple browser contexts |
| 25 | API Testing | `request` context, GET/POST/PUT/DELETE, API assertions |
| 26 | Authentication | Login flows, session storage, state management, reusable auth |
| 27 | Screenshots & Videos | Capturing screenshots, recording videos, tracing for debugging |
| 28 | Test Hooks | `beforeAll`, `afterAll`, `beforeEach`, `afterEach`, test isolation |
| 29 | Test Suites & Groups | Organizing tests, `describe()` blocks, tagging, skipping tests |
| 30 | Parallel Execution | Workers, sharding, configuring parallel runs |

### Phase 4: Playwright Advanced

| Day | Topic | Details |
|-----|-------|---------|
| 31 | Page Object Model (POM) | Design patterns for maintainable test code, base pages |
| 32 | Data-Driven Testing | Parameterized tests, CSV/JSON data sources, fixtures |
| 33 | Fixtures & Custom Fixtures | Built-in fixtures, creating custom fixtures, fixture scopes |
| 34 | Reporters | Built-in reporters (list, dot, HTML, JSON), custom reporters, CI integration |
| 35 | Configuration Deep Dive | Projects, browsers, devices, viewport, headless mode, retries |
| 36 | CI/CD Integration | GitHub Actions, Jenkins, Azure DevOps, running tests in pipelines |
| 37 | Visual Testing | Screenshot comparison, pixel diff, handling dynamic content |
| 38 | Performance Testing | Measuring load times, network interception, performance metrics |
| 39 | Component Testing | Testing isolated UI components with Playwright |
| 40 | E2E Project | Building a complete end-to-end test suite for a real application |

---

## VS Code Shortcuts

A comprehensive reference of VS Code keyboard shortcuts for Windows is available in:

📄 **[VS_Code_keyboard_shortcut_windows.md](./VS_Code_keyboard_shortcut_windows.md)**

Includes shortcuts for:
- General commands
- Basic editing
- Navigation
- Search & Replace
- Multi-cursor & Selection
- Rich language editing
- Editor & File management
- Debug & Terminal
- Extensions & Git

---

## How to Run

### Prerequisites
- [Node.js](https://nodejs.org/) installed (v18+ recommended)
- [VS Code](https://code.visualstudio.com/) installed

### Running JavaScript Files

```bash
# Navigate to the project folder
cd LEARNPLAYWRIGHTBATCH2X

# Run a specific JavaScript file
node chapter_01_Basics/01_Basics.js
```

### Running Playwright Tests (Upcoming)

```bash
# Install dependencies
npm install

# Run all tests
npx playwright test

# Run in headed mode (visible browser)
npx playwright test --headed

# Run a specific test file
npx playwright test tests/example.spec.ts

# Generate HTML report
npx playwright show-report
```

---

## Resources

### JavaScript Learning
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [JavaScript.info](https://javascript.info/)
- [ECMAScript Specification](https://tc39.es/ecma262/)

### Playwright Official
- [Playwright Documentation](https://playwright.dev/)
- [Playwright API Reference](https://playwright.dev/docs/api/class-playwright)
- [Playwright Test Assertions](https://playwright.dev/docs/test-assertions)

### Practice Platforms
- [The Testing Academy](https://thetestingacademy.com/)
- [Playwright Test Examples](https://github.com/microsoft/playwright/tree/main/examples)

---

## Author

**Swaraj M** | [The Testing Academy - Batch 2X]

---

> 💡 *"The best way to learn automation is to write tests every day. Consistency beats intensity."*
