# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`location = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "hello_world"
version = "0.1.0"
authors = ["imran82ali <code.imranali@gmail.com>"]
edition = "2018"
GitHub = https://github.com/scorpasdzx/location.git

[dependencies]
location = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use location;
fn main() {
    location::ques3::location();
}
```
following will also work:
```
use pakistan::islamabad::piaic;
fn main() {
location();
    }
```

now `cargo run` for results
