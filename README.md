# Writing an OS in Rust 

Code and notes from Phil Oppermann's blog [https://os.phil-opp.com/](https://os.phil-opp.com/) 

## Notes

#### https://os.phil-opp.com/minimal-rust-kernel/ 

- `cargo build --target x86_64-blog_os.json` - error message: "target may not be installed" - continue with `build-std` config and run `rustup component add rust-src`
- `.cargo/config.toml` must be in the project directory not your home directory 
- **NB** run `cargo install bootimage` from your home dir! It should be compiled with your native toolchain not the project's 
- Don't forget `rustup component add llvm-tools-preview` 
- QEMU (windows) - install from https://www.qemu.org/download/#windows 

