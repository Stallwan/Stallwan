```rs
fn main() {
    let mut a = 1;
    let mut b = 1;
    let mut c = 1;

    loop {
        println!("{a}");
        a = a + b;
        b = a;
    }
}
```
