# Chapter 8. Case Study

## 8.1 Asterinas

[Asterinas](https://github.com/asterinas/asterinas) was built with an older toolchain (2025-02-01).
It can be built using the RAPx toolchain with only a few minor modifications.
The following command can be used:

```shell
cd ostd
cargo rapx -audit -- --target x86_64-unknown-none
```

