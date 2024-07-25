# Building

## Machine code

Run the following command to output machine code:

```bash
cargo build --target x64.json
```

## Bootable disc image

Ensure you have installed the `bootimage` helper through:

```bash
cargo install bootimage
```

Run the following command to output a bootable disc image:

```bash
cargo bootimage --target x85.json
```