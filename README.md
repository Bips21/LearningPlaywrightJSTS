# Learning Playwright JS/TS

A hands-on learning repository covering JavaScript fundamentals, prompt engineering, and QA concepts, with a foundation for browser automation using Playwright and TypeScript.

<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript logo" width="96">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://playwright.dev/">
    <img src="https://playwright.dev/img/playwright-logo.svg" alt="Playwright logo" width="96">
  </a>
</p>
<p align="center">
  Logos: <a href="https://github.com/devicons/devicon">JavaScript (Devicon)</a> · <a href="https://playwright.dev/">Playwright</a>
</p>

## Chapter Structure

| Chapter | Topics | Example |
| --- | --- | --- |
| [`00_Chapter_Prompt_Eng/Selenium_Framework/`](00_Chapter_Prompt_Eng/Selenium_Framework/) | RICEPOT prompt engineering, problem statements, anti-hallucination guidance, and QA templates | [Generic QA template](00_Chapter_Prompt_Eng/Selenium_Framework/04_RICEPOT_Generic_QA_Template.md) |
| [`01_Chapter_JS_Basics/`](01_Chapter_JS_Basics/) | Hello World and basic math | [Hello World](01_Chapter_JS_Basics/01_HelloWorld.js) |
| [`02_Chapter_JS_Keywords_Identifiers/`](02_Chapter_JS_Keywords_Identifiers/) | JavaScript engine, keywords, identifiers, declarations, and comments | [Identifier rules](02_Chapter_JS_Keywords_Identifiers/06_keyword_identifier_rules.js) |
| [`03_Chapter_JS_Literals/`](03_Chapter_JS_Literals/) | Numbers and other JavaScript literals, including null, undefined, BigInt, and special numeric values | [Special numeric values](03_Chapter_JS_Literals/17_Special_Numeric_Values.js) |
| [`04_Chapter_JS_Operators/`](04_Chapter_JS_Operators/) | Assignment, arithmetic, comparison, logical, string, ternary, and `typeof` operators | [Ternary operator](04_Chapter_JS_Operators/28_Ternary_Op.js) |
| [`05_Chapter_JS_Increment&Decrement_Operators/`](05_Chapter_JS_Increment%26Decrement_Operators/) | Pre/post increment and decrement, nullish coalescing, and practice questions | [Nullish coalescing](05_Chapter_JS_Increment%26Decrement_Operators/45_Nullish_Coalescing.js) |
| [`06_Chapter_If_Else_Statement_Condition/`](06_Chapter_If_Else_Statement_Condition/) | `if`, `if/else`, nested conditions, and multiple conditions | [If/else example](06_Chapter_If_Else_Statement_Condition/47_If_Else_Nested.js) |
| [`07_Chapter_Switch/`](07_Chapter_Switch/) | `switch` statements, grouped cases, and practice scenarios | [Switch example](07_Chapter_Switch/53_API_Switch.js) |
| [`08_Chapter_JS_UserInput/`](08_Chapter_JS_UserInput/) | Prompt-based input, Node.js readline, synchronous prompts, and reading from standard input | [Read from standard input](08_Chapter_JS_UserInput/62_FS_readfile.js) |

## Project Structure

```text
.
|-- .gitignore
|-- README.md
|-- 00_Chapter_Prompt_Eng/
|   `-- Selenium_Framework/
|       |-- 00_RICEPOT_Fullform.md
|       |-- 01_RICEPOT_Prompt.md
|       |-- 02_Problem_Statement.md
|       |-- 03_Anti_Hallucination.md
|       `-- 04_RICEPOT_Generic_QA_Template.md
|-- 01_Chapter_JS_Basics/
|   |-- 01_HelloWorld.js
|   `-- 02_Math.js
|-- 02_Chapter_JS_Keywords_Identifiers/
|   |-- 03_js_engine.js
|   |-- 04_let_engine.js
|   |-- 05_Keyword_Identifier.js
|   |-- 06_keyword_identifier_rules.js
|   |-- 07_Identifier_Rules.js
|   |-- 08_Comments.js
|   `-- 09_IQ.js
|-- 03_Chapter_JS_Literals/
|   |-- 10_Literal.js
|   |-- 11_Numberal.js
|   |-- 12_Null_Undefined.js
|   |-- 13_Null.js
|   |-- 14.Literals.js
|   |-- 15_Number_Part01.js
|   |-- 16_Number_Part02.js
|   |-- 17_Special_Numeric_Values.js
|   `-- 18_Undefined.js
|-- 04_Chapter_JS_Operators/
|   |-- 19_Arch.js
|   |-- 20_Assignment_Op.js
|   |-- 21_Arithmetic_Op.js
|   |-- 22_Comparison_Op.js
|   |-- 23_Logical_Op.js
|   |-- 24_Confusing_Comparison_Op.js
|   |-- 25_CC.js
|   |-- 26_Questions.js
|   |-- 27_String.js
|   |-- 28_Ternary_Op.js
|   |-- 29_Ternary_Operator.js
|   |-- 30_IQ.js
|   |-- 31_IQ.js
|   |-- 32_IQ.js
|   |-- 33_IQ.js
|   |-- 34_Nested_Ternary.js
|   |-- 35_IQ.js
|   |-- 36_IQ.js
|   `-- 37_TypeOf.js
|-- 05_Chapter_JS_Increment&Decrement_Operators/
|   |-- 38_ID_Pre_Increment.js
|   |-- 39_ID_Post_Increment.js
|   |-- 40_IQ.js
|   |-- 41_IQ.js
|   |-- 42_IQ.js
|   |-- 43_Decrement.js
|   |-- 44_DE.js
|   `-- 45_Nullish_Coalescing.js
|-- 06_Chapter_If_Else_Statement_Condition/
|   |-- 46_IF.js
|   |-- 47_If_Else_Nested.js
|   |-- 48_Ternary_Op_If_Else.js
|   `-- 49.Multiple_If_Else.js
|-- 07_Chapter_Switch/
|   |-- 50_Switch.js
|   |-- 51_IQ.js
|   |-- 52_IQ.js
|   |-- 53_API_Switch.js
|   |-- 54_Switch_Group.js
|   |-- 55_IQ.js
|   |-- 56_IQ.js
|   |-- 57_IQ.js
|   `-- 58_IQ.js
`-- 08_Chapter_JS_UserInput/
    |-- 59_UI.js
    |-- 60_Node_UI.js
    |-- 61_Prompt_Sync.js
    `-- 62_FS_readfile.js
```

## Learning Objectives

- Build confidence with JavaScript syntax and the Node.js runtime.
- Understand declarations, identifiers, literals, and JavaScript's primitive types.
- Practice operators and reason through common JavaScript questions.
- Establish a foundation for browser automation with Playwright and TypeScript.

## Run an Example

Install Node.js, then open a terminal at the repository root and run an individual JavaScript file:

```sh
node 01_Chapter_JS_Basics/01_HelloWorld.js
node 04_Chapter_JS_Operators/21_Arithmetic_Op.js
node 04_Chapter_JS_Operators/28_Ternary_Op.js
node 06_Chapter_If_Else_Statement_Condition/47_If_Else_Nested.js
node 07_Chapter_Switch/53_API_Switch.js
node "05_Chapter_JS_Increment&Decrement_Operators/45_Nullish_Coalescing.js"
```

Each example is a standalone script. The user-input examples may wait for input in the terminal; run one file at a time. `61_Prompt_Sync.js` uses the `prompt-sync` package.
