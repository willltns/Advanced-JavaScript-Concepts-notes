## JavaScript Runtime
- js engine: v8...
   - memory heap: memory allocation.
   - call stack: code gets read and executed.
- Web APIs
   - DOM
   - AJAX
   - Timeout
- Event Loop: Callback Queue

## Promise
an object that may produce a single value some time in the future. Either a resolved value, or a  reason that it's not resolved(rejected). three states: fulfilled, rejected, pending.

##### error handling
`.catch()`

## Async - Await (Promise)
##### error handling
try - catch

## ES9 (ES2018)
` for of ` to async - await ---> `for await (... of ...) {...}`

## Job Queue (Microtask Queue)
has higher priority than callback queue (task queue).

## Parallel. Sequence. Race.

## Concurrency & Parallelism
js --> `new Worker()`

node --> `const { spawn } = require('child_process')`  