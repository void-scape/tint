# Tint

*Tint* is a `no_std` library for handling colorspace conversions.

## Example

```rust
let srgb = Srgb::rgb(r, g, b);
let mut linear = srgb.to_linear();
linear *= 0.5;
let srgb = linear.to_srgb();
```
