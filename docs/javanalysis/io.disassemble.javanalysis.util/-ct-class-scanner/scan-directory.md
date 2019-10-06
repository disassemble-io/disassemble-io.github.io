---
title: CtClassScanner.scanDirectory - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util](../index.html) / [CtClassScanner](index.html) / [scanDirectory](./scan-directory.html)

# scanDirectory

`fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Scans the given directory for matching [CtClass](#).

### Parameters

`directory` - The [File](https://docs.oracle.com/javase/6/docs/api/java/io/File.html) directory to look within.

`predicate` - A filter for which [CtClass](#) should have the given [Consumer](#) ran on it.

`consumer` - The consumer to run on each of the [CtMethod](#) within the matching [CtClass](#).`fun scanDirectory(directory: `[`File`](https://docs.oracle.com/javase/6/docs/api/java/io/File.html)`): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, CtClass>`

Scans the given directory for matching [CtClass](#), putting it within a map.
The map key matches [CtClass.getName](#)

### Parameters

`directory` - The [File](https://docs.oracle.com/javase/6/docs/api/java/io/File.html) directory to look within.

**Return**
A map of [CtClass](#) within the [File](https://docs.oracle.com/javase/6/docs/api/java/io/File.html) directory, where the key is [CtClass.getName](#).

