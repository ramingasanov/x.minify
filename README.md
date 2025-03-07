Minify Extension for [Mecha](https://github.com/mecha-cms/mecha)
================================================================

![Code Size](https://img.shields.io/github/languages/code-size/mecha-cms/x.minify?color=%23444&style=for-the-badge)

This extension reduces the page size by removing unused white-spaces and comments in the HTML output.

---

Release Notes
-------------

### 3.0.0

 - [x] Updated for Mecha 3.0.0.

### 2.6.6

 - Fixed [#5](https://github.com/mecha-cms/x.minify/issues/5), [#6](https://github.com/mecha-cms/x.minify/issues/6).
 - Minified boolean HTML attributes, and inline CSS rules.
 - Refactor.

### 2.5.7

 - Fixed PHP minifier bug [#1](https://github.com/mecha-cms/x.minify/issues/1)
 - Fixed broken minified CSS when found an empty selector [#3](https://github.com/mecha-cms/x.minify/pull/3)

### 2.5.5

 - [./mecha-cms/mecha#96](https://github.com/mecha-cms/mecha/issues/96)

### 2.5.3

 - Hot fixes for JavaScript minifier.

### 2.5.2

 - Updated PHP minifier.

### 2.5.1

 - Added `Minify::JSON()` and `Minify::PHP()` methods.