### 1. Javascript Runtime

C++(V8) open source project

### 2. Single Thread

- OS
  - Resource
    - Thread x (n)
      - Process == Program
      - Code
      - Stack
      - Heap
      - Data

### 3. Non-Blocking I/O [Libuv]

- Input
- Output
- Not-Blocking = ( asynchronous - callback )

### 4. Event-Driven

- Handle Callback

nodejs app

```
memory heap <-> callstack [] <==[event loop]==> queue
==================== source code ====================
================ Main Single Thread ================= 12+ worker threads
```

##

Thread Pool[1,2,3,4]  
----- request[1]  
----- request[2]  
----- request[3]  
----- request[4]
