- Node.js is an _**open-source**_, _**cross-platform**_ JavaScript _**runtime environment**_ that executes JavaScript code outside of a web browser

### Characteristics

- It runs in a single process. Due to async nature of node.js it can handle multiple request without the hassle of managing thread.
- Node.js uses Google’s open-source, high-performance JavaScript and WebAssembly engine called V8. 
- ![[Pasted image 20240211093601.png]]

> This above image depicts how nodejs handles async code execution using its single thread. The web api can be replaced with node api in case of server execution.  

### When not to use node.js

- Node.js is still limited by the amount of processing power it can harness. Complex programs that require a lot of processing significantly can slow things down. While Node.js can handle asynchronous I/O functions with ease, it is not suitable for compute-intensive applications like machine learning.