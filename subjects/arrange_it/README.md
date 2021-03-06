## arrange_it

### Instructions

Create a function called `arrange_phrase` that takes a string literal as a phrase and returns it organized
Each word will have a number that indicates the position of that word

> This exercise will test the **heap allocation** of your function!
> So try your best to allocate the minimum data on the heap!

### Expected Function

```rust
fn arrange_phrase(phrase: &str) -> String {
}
```

### Notions

- https://doc.rust-lang.org/1.22.0/book/first-edition/the-stack-and-the-heap.html
- https://doc.rust-lang.org/std/primitive.str.html#method.split

### Usage

Here is a program to test your function

```rust
fn main() {
    println!("{:?}", initials("is2 Thi1s T4est 3a"));
}
```

And its output

```console
student@ubuntu:~/[[ROOT]]/test$ cargo run
"This is a Test"
student@ubuntu:~/[[ROOT]]/test$
```
