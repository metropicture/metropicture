# Local setup

<blockquote>

Ensure you have the `rustup` application installed in your environment.

Ensure you have installed the [QEMU machine emulator and virtualizer](https://www.qemu.org/download/) application, so that you may run the kernel inside your host environment.

</blockquote>

Run the following commands:

```bash
rustup target add x86_64-unknown-none
rustup component add rust-src
cargo install bootimage
```