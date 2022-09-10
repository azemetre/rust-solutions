# Command Line Rust

General thoughts and notes while reading the book.

## Tips & Tricks

`echo $?` shows what the last exit status was.

Leading underscore in a variable name `let _this` is functional. It tells rust
compiler that you don't intend to use this variable right now. Without the
underscore, the compiler would warn about unused variable.

## Chapter 1

### Truth or Consequences

Tests by default run concurrently. If you would like to run the tests in order,
you can run them on a single thread via: `cargo test -- --test-threads=1`

Learning to read test output is a skill in itself and takes practice. The
preceding test result is trying very hard to show you how the expected output
differs from the actual output.

Correctly reporting the exit status is a characteristic of well-behaved
command-line programs. The exit value is important because a failed process
used in conjunction with another process should cause the combination to fail.

## Chapter 2

### Test for Echo

`Cyclomatic Complexity` refers to the various ways all the parameters can be
combined.

Use `?` instead of `Result::unwrap` to unpack an `Ok` value or propagate an
`Err`. When doing this omit the final semlicolon to return this value

## Chapter 3

### On The Catwalk

## Chapter 4

### Head Aches

## Chapter 5

### Word To Your Mother

## Chapter 6

### Den Of Uniquity

## Chapter 7

### Finders Keepers

## Chapter 8

### Shave And A Haircut

## Chapter 9

### Jack The Grepper

## Chapter 10

### Boston Commons

## Chapter 11

### Tailor Swyfte

## Chapter 12

### Fortunate Son

## Chapter 13

### Rascalry

## Chapter 14

### Elless Island
