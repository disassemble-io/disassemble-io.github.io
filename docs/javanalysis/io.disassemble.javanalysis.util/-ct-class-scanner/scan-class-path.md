[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CtClassScanner](index.md) / [scanClassPath](./scan-class-path.md)

# scanClassPath

`fun scanClassPath(predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Scans the class path for matching [CtClass](#).

### Parameters

`predicate` - A filter for which [CtClass](#) should have the given [Consumer](#) ran on it.

`consumer` - The consumer to run on each of the [CtMethod](#) within the matching [CtClass](#).