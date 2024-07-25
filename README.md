# Metropicture

This repository is the Metropicture kernel in the Rust language.

## Status

Metropicture is a product following the tutorial [Writing an OS in Rust](https://os.phil-opp.com). It is initially designed for the BIOS initialization mode; in the future UEFI may be considered.

Current tutorial part: [Minimal Rust kernel: Printing to screen](https://os.phil-opp.com/minimal-rust-kernel/#printing-to-screen).

Currently the command `cargo run` is outputting:

```plain
   Compiling metropicture v0.1.0 (C:\Users\hydro\Downloads\Metropicture Repositories\metropicture)
    Finished `dev` profile [unoptimized + debuginfo] target(s) in 0.71s
     Running `bootimage runner target\x64\debug\metropicture`
error: could not execute process `bootimage runner target\x64\debug\metropicture` (never executed)

Caused by:
  program not found
```

## Building

Read the following files in case you wish to build or debug the kernel:

[Local setup](LOCALSETUP.md)

[Building](BUILDING.md) - Object code or disc image

[Running](RUNNING.md) - Debug the kernel

## License

Apache 2.0