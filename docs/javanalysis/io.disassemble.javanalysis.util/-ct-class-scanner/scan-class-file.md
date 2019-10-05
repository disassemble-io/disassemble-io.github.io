[javanalysis](../../index.md) / [io.disassemble.javanalysis.util](../index.md) / [CtClassScanner](index.md) / [scanClassFile](./scan-class-file.md)

# scanClassFile

`fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, predicate: Predicate<CtClass>?, consumer: Consumer<CtMethod>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Applies the given [Predicate](#) and [Consumer](#) against the class file.

### Parameters

`path` - The path of the .class file to act upon.

`predicate` - A filter for which [CtClass](#) should have the given [Consumer](#) ran on it.

`consumer` - The consumer to run on each of the [CtMethod](#) within the matching [CtClass](#).`fun scanClassFile(path: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): CtClass?`

Reads the given .class file path into a [CtClass](#) object.

### Parameters

`path` - The path of the .class file to read.

**Return**
A [CtClass](#) read from the given .class file.

