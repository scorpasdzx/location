# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`location = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "location"
version = "0.1.0"
authors = ["wajid ali"]
edition = "2020"
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
use location::ques3::location;
fn main() {
location();
    }
```

now `cargo run` for results
