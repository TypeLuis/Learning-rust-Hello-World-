`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh` -> Installation

### command Line
`cargo` -> is the package manager

`rustc` -> is the compiler 

`rustup` -> Installs Rust, switches versions, updates

---

`rustc hello.rs` -> compiles the program to file called hello

`./hello` -> runs the program, any changes made you're going to have to compile again with rustc projectname

`cargo new helloProject` -> Creates a folder with the file from current folder with the nessecary package packages 


`cd helloProject` -> `cargo run` -> runs the project from the src, also creates a target folder and cargo.lock

when creating cargo new project, it already inits a git so you can remove it to add everything with `rm -rf helloProject/.git`
