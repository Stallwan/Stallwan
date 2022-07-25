```rs
// Emblematic program of the two powers

fn main() {
    let mut a = 0;
    let mut b = 1;

    loop {
        println!("{a}");  
        a = a + b;
        b = a;
    }
}
```
