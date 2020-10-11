# Rust webserver on Windows.

This is an introduction into using rust with an example of a simple web server returning a hello world message.

First of before we can continue compiling this example we need some dependencies.

First go to the build tools site and download MSBuild and install C++ compiler. Restart is required.
https://visualstudio.microsoft.com/visual-cpp-build-tools/

After that we can go to the rust language page and download the rust binary with the cargo packaging system.
https://www.rust-lang.org/tools/install

After this installation have completed we can run rust in our command prompt.
Go to the project directory and run

```
cargo build
``` 

After all the dependencies have been install you should be able to find the binary ```rust-webserver.exe``` in ```target\debug```.