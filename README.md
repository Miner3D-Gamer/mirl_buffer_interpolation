# Mirl Buffer (0.0.0-alpha)

### Muffel - A crate defining `Buffer` and `ConstBuffer` for graphical purposes

<sub>For the cpu to silently scream!</sub>

<details>
<summary>Flags</summary>

### Default:

**Core**

- `std` (Default)
- `c_compatible`
- `all`

**Codec**

- `all_codecs`
- `serde`
- `bitcode`
- `wincode` (bitcode recommended)
- `zerocopy`
- `compactly`

**Enum**

- `all_enum_extensions`
- `strum`
- `enum_ext`

</details>

### Entry Points

> `prelude` not provided

This crate is so simple that all functions and the single enum sit surface level.

### Purpose

Add resizing up/down scaling to `Buffer` with several algorithms to choose from.

### Disclaimer

At the moment the functions want the raw color data and return color data. More convenient integration will be added next update.

### Origin

The story of this lib almost the same as [`mirl_buffer`](https://github.com/Miner3D-Gamer/mirl_buffer)s.

[`mirl_extensions`](https://github.com/Miner3D-Gamer/mirl_extensions) pulls from all logical crates, yet this lib needs the interpolation traits from that crate.

So this crate was created, extending `Buffer` while living way above it in the dependency tree.
