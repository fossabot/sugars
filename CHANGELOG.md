# Changes

## Unreleased ~ master

## 0.3.0
Add a number of macros to create smart pointers: `rc!`, `refcell!`, `cow!`, `arc!`, `mutex!`
Move the boxed module to pointers, related to smart pointer
Add a new macro `hash` that gives back the hash of passed expression (of course, as long the type implements `Hash` trait)

## 0.2.0
Implement 3 nested `cvec`
Implement 2 nested `cvec`
Improve of `cset` macro using `Iterators` methods (doesn't bring a lot of performance improvements, but the code is cleaner)
Macro `time` now prints to stderr and format the time to 6 digits after the dot
Improve of `cmap` macro using `Iterators` methods (doesn't bring a lot of performance improvements, but the code is cleaner)
Improve performance of `cvec` macro using `Iterators` methods

## 0.1.0
Add collections macro `hmap`, `hset`, `btmap`, `btset`
Add times macro `time`
Add times macro `sleep`
Add times macro `dur` to create `Duration`
Add macro `boxed` to create `Box`
Add comprehension macro `cset`
Add comprehension macro `cmap`
Add comprehension macro `cvec`
