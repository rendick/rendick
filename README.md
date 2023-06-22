[![Stand With Ukraine](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner2-direct.svg)](https://stand-with-ukraine.pp.ua/)

```rust
#[derive(Debug)]
struct About{
    name: String,
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
