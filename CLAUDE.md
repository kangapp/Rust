# Rust 项目

## CI 检查

- `cargo nextest run --all-targets` - 单元测试
- `cargo clippy --all-targets -- -D warnings` - 代码检查

## 注意事项

- 包名 `Rust` 不符合 snake_case 规范，已有 `#[allow(non_snake_case)]`
