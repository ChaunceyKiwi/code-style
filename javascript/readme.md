# JavaScript Style Guide

## 4. Formatting

### 4.3 Statements
* 4.3.2 Semicolons are required
    * Every statement must be terminated with a semicolon. Relying on automatic semicolon insertion is forbidden.

### 4.4 Column limit
* JavaScript code has a column limit of **80** characters. Except as noted below, any line that would exceed this limit must be line-wrapped.

### 4.6 Whitespace
#### 4.6.2 Horizontal whitespace
* Pref: No spaces between brackets in object literals.

## 5. Language features

### 5.2 Array literals
* 5.2.1 Use trailing commas
    * Include a trailing comma whenever there is a line break between the final element and the closing bracket.

### 5.5 Functions
* 5.5.3 Arrow functions 
    * Prefer arrow functions over the function keyword, particularly for nested functions.
    * It is a good practice to use parentheses even for single-argument arrows, since the code may still parse reasonably (but incorrectly) if the parentheses are forgotten when an additional argument is added.

### 5.6 String literals
* 5.6.1 Use single quotes
    * Ordinary string literals are delimited with single quotes `'`, rather than double quotes `"`.
    * If a string contains a single quote character, consider using a template string to avoid having to escape the quote

