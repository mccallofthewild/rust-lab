# 👨‍🔬 Rust Laboratory
<em>Experiments in Rust</em>

## Fizzbuzz
```rust
fn fizzbuzz() {
    for i in 0..251 {
        let start = if i % 3 != 0 { "" } else { "fizz" };
        let end = if i % 5 != 0 { "" } else { "buzz" };
        if start.len() + end.len() != 0 {
            println!("{}{}", start, end);
        } else {
            println!("{}", i);
        }
    }
}
```
