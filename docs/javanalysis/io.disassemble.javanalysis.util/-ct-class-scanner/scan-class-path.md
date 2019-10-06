---
title: CtClassScanner.scanClassPath - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util](../index.html) / [CtClassScanner](index.html) / [scanClassPath](./scan-class-path.html)

# scanClassPath

`fun scanClassPath(predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Scans the class path for matching [CtClass](#).

### Parameters

`predicate` - A filter for which [CtClass](#) should have the given [Consumer](#) ran on it.

`consumer` - The consumer to run on each of the [CtMethod](#) within the matching [CtClass](#).