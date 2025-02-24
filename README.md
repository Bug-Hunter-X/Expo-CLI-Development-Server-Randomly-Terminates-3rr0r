# Expo CLI Development Server Random Termination

This repository demonstrates a bug where the Expo CLI development server randomly terminates without providing any error messages. The behavior is inconsistent; sometimes the server runs fine for extended periods, while at other times it crashes within minutes.  No errors are reported in the console.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the project dependencies.
4. Run `expo start` to start the development server.
5. Observe the behavior of the development server.  It may run for a while before terminating unexpectedly.

## Potential Causes

- Resource exhaustion (memory, CPU, etc.).
- Conflicting packages or dependencies.
- Underlying system issues.
- Bugs within the Expo CLI itself.

## Workaround (expoBugSolution.js)