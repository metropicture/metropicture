# Metropicture

The Metropicture operating system codebase.

<details>

<summary>Status</summary>

### Status 1

Metropicture is an open source product following the tutorial [Writing an OS in Rust](https://os.phil-opp.com). It is initially designed for the BIOS initialization mode; in the future UEFI may be considered.

Current tutorial part: [Minimal Rust kernel: Printing to screen](https://os.phil-opp.com/minimal-rust-kernel/#printing-to-screen).

### Status 2

Currently migrating project structure conforming to the Booting or Create Disk Image section described in the [Bootloader crate home](https://github.com/rust-osdev/bootloader/blob/HEAD/docs/create-disk-image.md).

### Status 3

[Question](https://users.rust-lang.org/t/install-json-target-in-rustup/114985) about local target

Solved: install the official `x86_64-unknown-none` target and discard the `x64.json` specification from the repository.

### Status 4

Resuming tutorial.

</details>

## Building

Read the following files in case you need to build or debug the operating system:

[Local setup](docs/localsetup.md) - Requirements

[Building](docs/building.md) - Build object code or a disc image

[Running](docs/running.md) - Debug the operating system

## License

The codebase is modified from the `post-03` branch from the [Writing OS in Rust blog series](https://os.phil-opp.com/). It is both Apache 2.0 and MIT.