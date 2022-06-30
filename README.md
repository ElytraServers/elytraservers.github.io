# Elytra Servers Maven Center Repository

鞘翅中央库，用最原始的方式搭建 Maven 库。主要用于分发没法使用 JitPack 构建，且尚未添加到 Maven Central 的库。

## 使用鞘翅中央库

```kotlin
repositories {
    maven("https://elytraservers.github.io")
}
```

## 现有内容

### KhlKt

作者计划上传到 Maven Center 但是还没通过就把 Signing 等做了，导致无法直接构建。

```kotlin
implementation("io.github.zly2006", "khlkt", "0.1-SNAPSHOT")
```
