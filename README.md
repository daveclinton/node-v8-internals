# Node.js V8 Internals Learning

This repository documents my exploration of how JavaScript is compiled, optimized, and executed by the V8 engine in Node.js.

## Goals

- Understand V8’s Just-In-Time (JIT) compilation process
- Use Node.js flags like `--trace-opt`, `--trace-deopt`, `--inspect`
- Analyze function optimizations and de-optimizations
- Explore inline caching and hidden classes

## Structure

Each folder contains:
- A JavaScript file with the concept demo
- A README explaining what the code is showing
- Relevant Node.js command to run it

## Progress

- [x] Setup tracing for optimizations
- [ ] Explore deoptimizations
- [ ] Understand inline caching
- [ ] Analyze hidden classes and shape transitions
