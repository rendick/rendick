```rust
#[derive(Debug)]
struct About{
    nickname: String,
    os: String,
    ide: String,
    country: String,
    languages: String,
    technology: String,
}

fn main() {
    let about_me = About {
        name: String::from("Richard Benson"),
        os: String::from("Arch Linux + bspwm"),
        ide: String::from("VSCodium or Vim"),
        country: String::from("Ukraine"),
        languages: String::from("Rust, Bash Shell, JavaScript"),
        technology:  String::from("React + React Redux, Node.js, web3 + TronWeb"),
    };

    println!("{:?}", about_me);
}

```
