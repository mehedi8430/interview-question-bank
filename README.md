# JavaScript Interview Crack

---

### Table of Contents

<!-- TOC_START -->

| No. | Questions                                                                                                                                                                                                          |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1   | [What is the Runtime Environment](#what-is-the-runtime-environment)                                                                                                                                                |
| 2   | [What is a JS Engine](#what-is-a-js-engine)                                                                                                                                                                        |
| 3   | [How is JS Code Executed](#how-is-js-code-executed)                                                                                                                                                                |
| 4   | [What are the Main Components of a Runtime](#what-are-the-main-components-of-a-runtime)                                                                                                                            |
| 5   | [What is a Web API](#what-is-a-web-aPI)                                                                                                                                                                            |
| 6   | [What is JIT](#what-is-jit)                                                                                                                                                                                        |
| 7   | [What are V8, SpiderMonkey, and Nitro/JavaScriptCore](#what-are-v8-spidermonkey-and-nitro-or-javascriptcore)                                                                                                       |
| 8   | [What is AST and Bytecode](#what-is-ast-and-bytecode)                                                                                                                                                              |
| 9   | [What is the difference between var, let, and const](#what-is-the-difference-between-var-let-and-const)                                                                                                            |
| 10  | [Explain the event loop in JavaScript](#explain-the-event-loop-in-javaScript)                                                                                                                                      |
| 11  | [What are closures? Provide an example](#what-are-closures-provide-an-example)                                                                                                                                     |
| 12  | [How does JavaScript handle asynchronous operations](#how-does-javaScript-handle-asynchronous-operations)                                                                                                          |
| 13  | [Explain the difference between null and undefined](#explain-the-difference-between-null-and-undefined)                                                                                                            |
| 14  | [What is the this keyword in JavaScript? How does it behave in different contexts](#what-is-the-this-keyword-in-javaScript-how-does-it-behave-in-different-contexts)                                               |
| 15  | [Explain prototypal inheritance in JavaScript](#explain-prototypal-inheritance-in-javaScript)                                                                                                                      |
| 16  | [What are the differences between shallow copy and deep copy? How do you create a deep copy of an object](#what-are-the-differences-between-shallow-copy-and-deep-copy-how-do-you-create-a-deep-copy-of-an-object) |

<!-- TOC_END -->

<!-- QUESTIONS_START -->

1. ### What is the Runtime Environment

   In the context of JavaScript (JS), the runtime environment includes everything that is necessary to execute the code. Parts of Runtime Environment are JavaScript engine V8, memory management, and APIs.

2. ### What is a JS Engine

   A JavaScript engine is a program or an interpreter that executes JavaScript code. It parses the code, converts it into machine code, and then runs it. Examples of JS engines include Google's V8, Mozilla's SpiderMonkey, and Apple's Nitro/JavaScriptCore.

3. ### How is JS Code Executed

   The execution of JS code involves several steps:

   Parsing: The JavaScript engine parses the source code and generates an Abstract Syntax Tree (AST), which is a tree representation of the structure of the code.

   Compilation: Some engines use Just-In-Time (JIT) compilation to compile the AST into bytecode or machine code.

   Execution: The compiled code is then executed by the engine's runtime, where it interacts with the memory, the call stack, and the event loop.

   Garbage Collection: During execution, the engine also manages memory and performs garbage collection to free up space used by objects that are no longer needed.

4. ### What are the Main Components of a Runtime

   Call Stack: The call stack keeps track of function calls. It manages the execution context, allowing the engine to know which function is currently running and what should happen next.

   Heap: The heap is a large, unstructured region of memory where objects are stored. It's used for dynamic memory allocation.

   Event Loop: The event loop handles asynchronous operations, such as events, timers, and promises. It checks the call stack and the message queue, processing tasks and ensuring non-blocking execution.

   Web APIs: These are provided by the browser or the environment (e.g., Node.js) and allow JavaScript to interact with external resources, like the DOM, networking, or file systems.

5. ### What is a Web API

   A Web API is an interface provided by web browsers or environments like Node.js that allows JavaScript to interact with features outside the core language, such as the DOM, network requests, or storage.

   Examples include:

   DOM API: Manipulates HTML and CSS.

   Fetch API: Performs network requests.

   LocalStorage API: Stores data locally in the browser.

   WebRTC API: Enables real-time communication.

6. ### What is JIT

   JIT (Just-In-Time) compilation is a method of executing code that involves compiling the code during execution rather than before execution. This allows for optimizations based on the actual runtime conditions, which can improve performance.

7. ### What are V8, SpiderMonkey and Nitro or JavaScriptCore

   V8: Google's JavaScript engine, used in Chrome and Node.js.

   SpiderMonkey: Mozilla's JavaScript engine, used in Firefox.

   Nitro/JavaScriptCore: Apple's JavaScript engine, used in Safari.

8. ### What is AST and Bytecode

   AST (Abstract Syntax Tree): A tree representation of the structure of the source code. It’s generated during the parsing phase and is used as an intermediate step in the compilation process.

   Bytecode: A lower-level, optimized set of instructions generated from the AST. Bytecode is often executed by a virtual machine rather than directly by the hardware.

9. ### What is the difference between var, let, and const

10. ### Explain the event loop in JavaScript

11. ### What are closures? Provide an example

12. ### How does JavaScript handle asynchronous operations

13. ### Explain the difference between null and undefined

14. ### What is the this keyword in JavaScript? How does it behave in different contexts

15. ### Explain prototypal inheritance in JavaScript

16. ### What are the differences between shallow copy and deep copy? How do you create a deep copy of an object

17. ### What is a higher-order function? Give an example

18. ### Explain the difference between map, forEach, filter, and reduce

<!-- QUESTIONS_END -->
