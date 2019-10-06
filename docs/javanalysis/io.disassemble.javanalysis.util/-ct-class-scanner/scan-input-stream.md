---
title: CtClassScanner.scanInputStream - javanalysis
---

[javanalysis](../../index.html) / [io.disassemble.javanalysis.util](../index.html) / [CtClassScanner](index.html) / [scanInputStream](./scan-input-stream.html)

# scanInputStream

`fun scanInputStream(inputStream: `[`InputStream`](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Reads the [InputStream](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) into a [CtClass](#) object.

### Parameters

`inputStream` - An [InputStream](https://docs.oracle.com/javase/6/docs/api/java/io/InputStream.html) representing a .class file.

`predicate` - A filter for which [CtClass](#) should have the given [Consumer](#) ran on it.

`consumer` - The consumer to run on each of the [CtMethod](#) within the matching [CtClass](#).