```rust
// Emblematic program of the two powers

fn main() {
    let mut a = 1;
    let mut b = 1;

    loop {
        println!("{a}");  
        a += b;
        b = a;
    }
}
```
