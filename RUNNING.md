# Running

Ensure you have installed the `bootimage` helper through:

```bash
cargo install bootimage
```

Run the kernel in QEMU through:

```plain
cargo xrun --target x64.json -- [QEMU arguments]
```