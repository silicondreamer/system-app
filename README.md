# system-app
A Rust test application dependent on cli-lib

## install/update rustc and cargo:
rustup update stable

## create a repository directory and clone the code + dependency
mkdir devel
cd devel
git clone https://github.com/silicondreamer/system-app.git
git clone https://github.com/silicondreamer/cli-lib.git


# build the application top level
cd system-app
cargo build
cargo run

# enjoy the two registered command, "test" and "exit" !

![image](https://user-images.githubusercontent.com/30495614/152697676-68a9fa98-f48c-41d3-a486-a041001ecca8.png)

