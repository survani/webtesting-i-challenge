## How to start a test in a pure function

- basic adding pure function

  function add (a, b) {
  return a + b;
  }

the funtion above adds two numbers. Now lets test this...

-- start with low hanging fruit ==> happy path ( your basic assumptions)
-- then check for invalid input
-- then move on to edge cases

> Always make your tests fail...
